# Laravel 11 Reverb 2 Way Demo

## Description
This project demonstrates the two-way or bi-directional Laravel Reverb websocket functionality in a Laravel 11 environment. It serves as a simple example for educational and demonstration purposes. The project showcases how to implement, manage, and configure  Laravel Reverb + Laravel Echo in a web application.

### Mainly includes:
- Laravel 11
- Reverb
- Laravel Echo
- Vue
- Laravel Breeze

### Features
- Laravel 11 setup
- Demonstrates two-way reverb effect integration
- Easy to follow and customizable

## Requirements

Same as Laravel 11 requirements, can be found here: **[https://laravel.com/docs/11.x/deployment#server-requirements](https://laravel.com/docs/11.x/deployment#server-requirements)**

## Installation

Run the following commands in terminal:

1. Clone the repository:

```bash
git clone https://github.com/yourusername/laravel-11-reverb-demo.git
cd laravel-11-reverb-demo
```

2. Install dependencies:
```bash
composer install
```

3. Copy the .env.example file to .env and update it with your environment variables.
```bash
cp .env.example .env
```

4. Install Laravel Reverb broadcasting config
```bash
php artisan install:broadcasting
```

5. Configure Reveb application credentials in env
```bash
REVERB_APP_ID=my-app-id
REVERB_APP_KEY=my-app-key
REVERB_APP_SECRET=my-app-secret
```

6. Generate an application key:
```bash
php artisan key:generate
```

7. Configure Database credentials in env
```bash
DB_CONNECTION=
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=
DB_USERNAME=root
DB_PASSWORD=
```

8. Run the database migrations:
```bash
php artisan migrate
```

9. Install node packages and build:
```bash
pnpm install
pnpm build
```

10. Serve the application:
```bash
php artisan serve
php artisan reverb:start
```

## Usage

After installation, you can access the demo by visiting __http://localhost:8000__

By default, websocket connection will be listening to port __6001__. It can be changed in .env  __REVERB_SERVER_PORT__

## Liscense

This project is licensed under the [MIT license](https://opensource.org/licenses/MIT).

## Sources

[https://laravel.com/docs/11.x/broadcasting](https://laravel.com/docs/11.x/broadcasting)

[https://laravel.com/docs/11.x/reverb](https://laravel.com/docs/11.x/reverb)

[https://laravel.com/docs/11.x/starter-kits#laravel-breeze](https://laravel.com/docs/11.x/starter-kits#laravel-breeze)


## Project status

Currently under development