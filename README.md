
## About

This repo is created to validate a use case of the package [laravel-routes-attributes](https://github.com/spatie/laravel-route-attributes) by Spatie.

An [issue](https://github.com/spatie/laravel-route-attributes/issues/57) was reported. It claims that there is a conflict between controllers with the same class name.

This project aims to show that the issue doesn't exist.

Although, if you have 2 controllers with the same class name and same namespace, an error occurs, as expected.

### Check the routes

Three routes are registered, each one in different controllers that have the same name but different namespace.

The routes are:
* my-route
* api-route
* admin-route
