## Installation

### Setup

1. Clone the repository and open the project directory.

```bash
git https://github.com/MohamedELdarwish1/ChatApp.git && cd ChatApp
```

2. Install Composer dependencies.

```bash
composer install
```

3. copy environment variables.

```bash
cp .env.example .env
```

4. Generate Laravel application key.

```bash
php artisan key:generate
```

5. Install Node.js dependencies and compile frontend assets.

```bash
npm install
```

6. Run database migrations and populate the database with some dummy data.

```bash
php artisan migrate:fresh --seed
```

7. run the app dev.
 ```bash
npm run dev 
```

8. Start Laravel's local development server.

```bash
php artisan serve
```
9. Start Laravel's socket server.

```bash
php artisan websocket:serve
```

10. register an acoount and login 

11. At this point, the application should be ready to go at http://localhost:8000/ 

12.  Go to webSocket Dashboard  http://localhost:8000/chat-websockets .
