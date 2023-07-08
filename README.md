# Laravel Breeze API Scaffold

A minimal and lightweight authentication scaffolding for Laravel applications, designed for API authentication. Built on top of Laravel Breeze, it simplifies the setup process by providing pre-built controllers, routes, and views for tasks such as registration, login, password reset, and email verification. It leverages Laravel Sanctum (formerly Laravel Airlock) for API token-based authentication.

## Table of Contents
- [About Laravel](#about-laravel)
- [Learning Laravel](#learning-laravel)
- [Breeze API](#breeze-api)
- [Laravel Sanctum](#laravel-sanctum)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## About Laravel
Laravel is a web application framework with expressive, elegant syntax. It provides a pleasant and creative development experience by easing common tasks used in many web projects. Some of its features include simple routing, powerful dependency injection, multiple back-ends for session and cache storage, a database ORM, schema migrations, robust job processing, and real-time event broadcasting.

## Learning Laravel
Laravel has extensive and thorough documentation, along with a video tutorial library, making it easy to get started. Check out the [official Laravel documentation](https://laravel.com/docs/10.x) and the [Laravel Bootcamp](https://bootcamp.laravel.com/) for guided tutorials. If you prefer video tutorials, Laracasts offers over 2000 videos covering Laravel, modern PHP, unit testing, and JavaScript.

## Breeze API
Breeze API provides a minimal and lightweight authentication scaffolding for Laravel applications. It simplifies API authentication by offering pre-built controllers, routes, and views for common tasks like registration, login, password reset, and email verification. It works with Laravel's built-in authentication features and utilizes Laravel Sanctum for API token-based authentication.

To learn more about Breeze API, check out the [documentation](https://laravel.com/docs/10.x/starter-kits#breeze-and-next).

## Laravel Sanctum
Laravel Sanctum is a lightweight, stateless authentication system for API authentication in Laravel. It secures API endpoints using tokens without the complexity of setting up a full OAuth server. Sanctum uses JSON Web Tokens (JWT) for API token-based authentication. It generates secure tokens that clients can use to authenticate and access protected API routes. To learn more, see the [Sanctum documentation](https://laravel.com/docs/10.x/sanctum).

## Installation
Before proceeding with the configuration, make sure you have Composer, PHP, and Laravel installed. For detailed installation instructions, refer to the official Laravel installation guide. It's recommended to use Docker if possible.

Follow these steps to get started:
1. Clone the repository:
```bash
  git clone git@github.com:Igor-Ponso/laravel-breeze-api-sanctum-scaffold.git
```
2. Open the repository in your code editor.
3. Update and install Composer dependencies:
```bash
  composer upgrade
```
   composer upgrade

## Configuration
After cloning the repository and installing the dependencies, modify the .env.example file to **`.env`**. Then, update the following environment variables in the .env file according to your project's setup:

For production:
- **`APP_URL`**: Your project's API domain.
- **`FRONTEND_URL`**: Your project's frontend domain.
- **`SANCTUM_STATEFUL_DOMAINS`**: Your project's frontend domain.
- **`SESSION_DOMAIN`**: Your project's domain.

If you are using subdomains, make sure to include a . before the domain:
```env
SESSION_DOMAIN=.mydomain.com
```

Refer to the [Sanctum documentation](https://laravel.com/docs/10.x/sanctum#spa-authentication) for additional configuration details.

## Usage
Once you have completed the installation and configuration steps, run the following command to start the Laravel development server:
php artisan serve

You can now access your Laravel application and utilize the Breeze API authentication scaffolding with Laravel Sanctum.

## Contributing
Contributions to this project are welcome. To contribute, please follow the guidelines for bug reports, feature requests, and pull requests.

## License
This project is open-source and released under the MIT License.

Feel free to modify the above template according to your requirements. The refactored version incorporates the tips I provided, including a table of contents, improved formatting and styling, installation instructions, configuration details, usage examples, contributing guidelines, and license information.
