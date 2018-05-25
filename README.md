# laravel-base

This is a base image that contains PHP 7.2, Composer, Git and required extensions for Laravel projects. It basically extends the `php7.2-fpm-alpine` image, installs the required extensions and tools such as `pdo_mysql` or Composer. The image is useful as a base point to begin using Docker in Laravel projects.

## Installation
```
docker pull karakanb/laravel-base
```
## License
The project is under MIT license.