# TCH_Lab11 - Sprawozdanie - Docker Compose

Przebieg zadania:
1. Uruchomienie usług zdefiniowanych w pliku docker-compose.yml poprzez utworzenie i uruchomienie kontenerów dla każdej usługi
    ```
    docker compose up -d
    ```
    ![image](https://github.com/krystiancz21/TCH_L11/blob/f452763c154ff6f6d9ab1b7330257ae204ef1f7a/TCH11ss1.png)

2. Aby uzyskać dostęp do ograniczonego portu 6666, należy zezwolić na to w przeglądarce:
    ![image](https://github.com/krystiancz21/TCH_L11/blob/f452763c154ff6f6d9ab1b7330257ae204ef1f7a/TCH11ss4.png)

3. Wyświetlenie zawartości pliku index.php i strony logowania do phpMyAdmin:
    ![image](https://github.com/krystiancz21/TCH_L11/blob/f452763c154ff6f6d9ab1b7330257ae204ef1f7a/TCH11ss2.png)

4. Zalogowanie i utworzenie testowej bazy:
    ![image](https://github.com/krystiancz21/TCH_L11/blob/f452763c154ff6f6d9ab1b7330257ae204ef1f7a/TCH11ss3.png)

5. Zatrzymanie i usunięcie kontenerów
    ```
    docker compose down
    ```
