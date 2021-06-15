# Packagify

A basic Laravel Package scaffolder

Package is in development.

Package is created to scaffold laravel package.

# Installation

You can install the package via composer:

```
composer require jagdish-j-p/packagify
```

Then run the publish command to publish the config file to edit packagify configuration.

```
php artisan vendor:publish --provider="JagdishJP\Packagify\Providers\PackagifyServiceProvider"
```

to add/remove package directories edit config/packagify.php file

```
'packageStructure' => ["config", "database", "database\\factories", "database\\migrations", "database\\seeders", "public", "resources", "resources\\lang", "resources\\views", "resources\\lang\\en", "routes", "src", "src\\Console", "src\\Console\\Commands", "src\\Http", "src\\Http\\Controllers", "src\\Http\\Middleware", "src\\Models", "src\\Providers"]
```

**packageStructure** contains list of directories to create for your package. You can add or remove any directory.

# Usage

```
php artisan package:create
```

Follow the instructions and your package will be created.
