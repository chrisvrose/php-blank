# php-start

Simple apache-php server mapped to port **8080**. 
The `./src` folder is mapped to `/var/www/html`, so just use accordingly.
## Usage

```sh
docker-compose up -d
```

## Why

Use for quick and dirty PHP testing.

`./src` is mapped readonly to the container.

## Note for SELINUX

Instead of `:ro` you may have to append `:z`. (Possible solution, not definite)