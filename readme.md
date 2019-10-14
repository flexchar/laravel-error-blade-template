## Laravel Error Example

This repo showcases an error _No hint path defined for [errors]_.

GitHub issue https://github.com/laravel/framework/issues/30226.

The desired behaviour is that built-in welcome page should show clean simple message by extending built-in blade template for errors. Instead it throws an error.

To try:

1. `composer install`
2. `php artisan serve`
3. Investigate at http://localhost:8000/

This was working fine till Laravel 5.8.
