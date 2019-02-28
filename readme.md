# PhpUnit Runner

A PhpUnit runner for environments where Xdebug is installed, since Xdebug slows down tests when the extension is loaded. 

## Installation

```bash
composer require --dev dbt/phpunit-runner
```

## Usage

```bash
php vendor/dbt/phpunit-runner/phpunit.php
```

## Caveats

Long-running test stacks may require a custom timeout to be passed in.

## License

MIT. Do as you wish.
