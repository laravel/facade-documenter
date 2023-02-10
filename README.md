# Facade Documenter

```sh
# Configure composer
composer config repositories.facade-documenter vcs git@github.com:laravel-labs/facade-documenter.git

# Install the package
composer require --dev laravel/facade-documenter:dev-main

# Update the docblocks:
php -f vendor/bin/facade.php -- \
    Illuminate\\Support\\Facades\\App \
    Illuminate\\Support\\Facades\\Artisan \
    Illuminate\\Support\\Facades\\Auth \
    ...

# Lint the docblocks:
php -f vendor/bin/facade.php -- --lint \
    Illuminate\\Support\\Facades\\App \
    Illuminate\\Support\\Facades\\Artisan \
    Illuminate\\Support\\Facades\\Auth \
    ...
```
