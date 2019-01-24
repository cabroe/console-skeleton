Console Skeleton
================

Skeleton for a console application, including:
* DI-Container
* Services and commands [autowired in yaml-config](config/services.yaml)
* [Example Command](src/Command/ExampleCommand.php)
* [Example test](tests/Command/ExampleCommandTest.php)

## Getting started

This will create a new project with the skeleton for a console application:

```bash
composer create-project hmazter/console-skeleton the-new-app-name
cd the-new-app-name
```

The skeleton can then be executed with:
```bash
./app
```

### Running with docker

Build the app with:
```bash
docker-compose build
```

And run the app with docker with this command:
```bash
docker-compose run console ./app
```

### Tests

Tests can be run with:
```bash
composer test
```

### Continue building

Go ahead and:
* Edit/replace command in src/Commad/ExampleCommand
* Add more commands in src/Command
* Add additional classed that you need in src/
* Edit/replace the test in tests/Command/ExampleCommandTest