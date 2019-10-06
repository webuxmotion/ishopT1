## 1. Create folders
```
mkdir app
mkdir app/controllers
mkdir app/models
mkdir app/views
mkdir app/widgets
mkdir config
mkdir public
mkdir tmp
```

## 2. Create file 'composer.json'
```
{
  "autoload": {
    "psr-4": {
      "ishop\\": "vendor/ishop",
      "app\\": "app"
    }
  },
  "require": {}
}
```

## 3. Install composer
```
composer install
```

## 4. Create folders for our core
```
mkdir vendor/ishop
mkdir vendor/ishop/core
mkdir vendor/ishop/core/base
mkdir vendor/ishop/core/libs
```
