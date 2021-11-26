# laravel-install
laravel installation
NUC@NUC_LAB1 MINGW64 ~/Desktop
$ composer
   ______
  / ____/___  ____ ___  ____  ____  ________  _____
 / /   / __ \/ __ `__ \/ __ \/ __ \/ ___/ _ \/ ___/
/ /___/ /_/ / / / / / / /_/ / /_/ (__  )  __/ /
\____/\____/_/ /_/ /_/ .___/\____/____/\___/_/
                    /_/
Composer version 2.0.9 2021-01-27 16:09:27

Usage:
  command [options] [arguments]

Options:
  -h, --help                     Display this help message
  -q, --quiet                    Do not output any message
  -V, --version                  Display this application version
      --ansi                     Force ANSI output
      --no-ansi                  Disable ANSI output
  -n, --no-interaction           Do not ask any interactive question
      --profile                  Display timing and memory usage information
      --no-plugins               Whether to disable plugins.
  -d, --working-dir=WORKING-DIR  If specified, use the given directory as working directory.
      --no-cache                 Prevent use of the cache
  -v|vv|vvv, --verbose           Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

Available commands:
  about                Shows the short information about Composer.
  archive              Creates an archive of this composer package.
  browse               Opens the package's repository URL or homepage in your browser.
  cc                   Clears composer's internal package cache.
  check-platform-reqs  Check that platform requirements are satisfied.
  clear-cache          Clears composer's internal package cache.
  clearcache           Clears composer's internal package cache.
  config               Sets config options.
  create-project       Creates new project from a package into given directory.
  depends              Shows which packages cause the given package to be installed.
  diagnose             Diagnoses the system to identify common errors.
  dump-autoload        Dumps the autoloader.
  dumpautoload         Dumps the autoloader.
  exec                 Executes a vendored binary/script.
  fund                 Discover how to help fund the maintenance of your dependencies.
  global               Allows running commands in the global composer dir ($COMPOSER_HOME).
  help                 Displays help for a command
  home                 Opens the package's repository URL or homepage in your browser.
  i                    Installs the project dependencies from the composer.lock file if present, or falls back on the composer.json.
  info                 Shows information about packages.
  init                 Creates a basic composer.json file in current directory.
  install              Installs the project dependencies from the composer.lock file if present, or falls back on the composer.json.
  licenses             Shows information about licenses of dependencies.
  list                 Lists commands
  outdated             Shows a list of installed packages that have updates available, including their latest version.
  prohibits            Shows which packages prevent the given package from being installed.
  remove               Removes a package from the require or require-dev.
  require              Adds required packages to your composer.json and installs them.
  run                  Runs the scripts defined in composer.json.
  run-script           Runs the scripts defined in composer.json.
  search               Searches for packages.
  self-update          Updates composer.phar to the latest version.
  selfupdate           Updates composer.phar to the latest version.
  show                 Shows information about packages.
  status               Shows a list of locally modified packages.
  suggests             Shows package suggestions.
  u                    Upgrades your dependencies to the latest version according to composer.json, and updates the composer.lock file.
  update               Upgrades your dependencies to the latest version according to composer.json, and updates the composer.lock file.
  upgrade              Upgrades your dependencies to the latest version according to composer.json, and updates the composer.lock file.
  validate             Validates a composer.json and composer.lock.
  why                  Shows which packages cause the given package to be installed.
  why-not              Shows which packages prevent the given package from being installed.

NUC@NUC_LAB1 MINGW64 ~/Desktop
$ composer create-project laravel/laravel example-app
Creating a "laravel/laravel" project at "./example-app"
Installing laravel/laravel (v8.6.8)
  - Downloading laravel/laravel (v8.6.8)
  - Installing laravel/laravel (v8.6.8): Extracting archive
Created project in C:\Users\NUC\Desktop\example-app
> @php -r "file_exists('.env') || copy('.env.example', '.env');"
Loading composer repositories with package information
Updating dependencies
Lock file operations: 111 installs, 0 updates, 0 removals
  - Locking asm89/stack-cors (v2.0.3)
  - Locking brick/math (0.9.3)
  - Locking dflydev/dot-access-data (v3.0.1)
  - Locking doctrine/inflector (2.0.4)
  - Locking doctrine/instantiator (1.4.0)
  - Locking doctrine/lexer (1.2.1)
  - Locking dragonmantank/cron-expression (v3.1.0)
  - Locking egulias/email-validator (2.1.25)
  - Locking facade/flare-client-php (1.9.1)
  - Locking facade/ignition (2.17.1)
  - Locking facade/ignition-contracts (1.0.2)
  - Locking fakerphp/faker (v1.16.0)
  - Locking filp/whoops (2.14.4)
  - Locking fruitcake/laravel-cors (v2.0.4)
  - Locking graham-campbell/result-type (v1.0.4)
  - Locking guzzlehttp/guzzle (7.4.0)
  - Locking guzzlehttp/promises (1.5.1)
  - Locking guzzlehttp/psr7 (2.1.0)
  - Locking hamcrest/hamcrest-php (v2.0.1)
  - Locking laravel/framework (v8.73.2)
  - Locking laravel/sail (v1.12.6)
  - Locking laravel/sanctum (v2.12.2)
  - Locking laravel/serializable-closure (v1.0.4)
  - Locking laravel/tinker (v2.6.2)
  - Locking league/commonmark (2.0.2)
  - Locking league/config (v1.1.1)
  - Locking league/flysystem (1.1.7)
  - Locking league/mime-type-detection (1.9.0)
  - Locking mockery/mockery (1.4.4)
  - Locking monolog/monolog (2.3.5)
  - Locking myclabs/deep-copy (1.10.2)
  - Locking nesbot/carbon (2.54.0)
  - Locking nette/schema (v1.2.2)
  - Locking nette/utils (v3.2.6)
  - Locking nikic/php-parser (v4.13.1)
  - Locking nunomaduro/collision (v5.10.0)
  - Locking opis/closure (3.6.2)
  - Locking phar-io/manifest (2.0.3)
  - Locking phar-io/version (3.1.0)
  - Locking phpdocumentor/reflection-common (2.2.0)
  - Locking phpdocumentor/reflection-docblock (5.3.0)
  - Locking phpdocumentor/type-resolver (1.5.1)
  - Locking phpoption/phpoption (1.8.0)
  - Locking phpspec/prophecy (1.14.0)
  - Locking phpunit/php-code-coverage (9.2.9)
  - Locking phpunit/php-file-iterator (3.0.5)
  - Locking phpunit/php-invoker (3.1.1)
  - Locking phpunit/php-text-template (2.0.4)
  - Locking phpunit/php-timer (5.0.3)
  - Locking phpunit/phpunit (9.5.10)
  - Locking psr/container (1.1.2)
  - Locking psr/event-dispatcher (1.0.0)
  - Locking psr/http-client (1.0.1)
  - Locking psr/http-factory (1.0.1)
  - Locking psr/http-message (1.0.1)
  - Locking psr/log (2.0.0)
  - Locking psr/simple-cache (1.0.1)
  - Locking psy/psysh (v0.10.11)
  - Locking ralouphie/getallheaders (3.0.3)
  - Locking ramsey/collection (1.2.2)
  - Locking ramsey/uuid (4.2.3)
  - Locking sebastian/cli-parser (1.0.1)
  - Locking sebastian/code-unit (1.0.8)
  - Locking sebastian/code-unit-reverse-lookup (2.0.3)
  - Locking sebastian/comparator (4.0.6)
  - Locking sebastian/complexity (2.0.2)
  - Locking sebastian/diff (4.0.4)
  - Locking sebastian/environment (5.1.3)
  - Locking sebastian/exporter (4.0.4)
  - Locking sebastian/global-state (5.0.3)
  - Locking sebastian/lines-of-code (1.0.3)
  - Locking sebastian/object-enumerator (4.0.4)
  - Locking sebastian/object-reflector (2.0.4)
  - Locking sebastian/recursion-context (4.0.4)
  - Locking sebastian/resource-operations (3.0.3)
  - Locking sebastian/type (2.3.4)
  - Locking sebastian/version (3.0.2)
  - Locking swiftmailer/swiftmailer (v6.3.0)
  - Locking symfony/console (v5.3.11)
  - Locking symfony/css-selector (v5.3.4)
  - Locking symfony/deprecation-contracts (v2.5.0)
  - Locking symfony/error-handler (v5.3.11)
  - Locking symfony/event-dispatcher (v5.3.11)
  - Locking symfony/event-dispatcher-contracts (v2.5.0)
  - Locking symfony/finder (v5.3.7)
  - Locking symfony/http-client-contracts (v2.5.0)
  - Locking symfony/http-foundation (v5.3.11)
  - Locking symfony/http-kernel (v5.3.12)
  - Locking symfony/mime (v5.3.11)
  - Locking symfony/polyfill-ctype (v1.23.0)
  - Locking symfony/polyfill-iconv (v1.23.0)
  - Locking symfony/polyfill-intl-grapheme (v1.23.1)
  - Locking symfony/polyfill-intl-idn (v1.23.0)
  - Locking symfony/polyfill-intl-normalizer (v1.23.0)
  - Locking symfony/polyfill-mbstring (v1.23.1)
  - Locking symfony/polyfill-php72 (v1.23.0)
  - Locking symfony/polyfill-php73 (v1.23.0)
  - Locking symfony/polyfill-php80 (v1.23.1)
  - Locking symfony/polyfill-php81 (v1.23.0)
  - Locking symfony/process (v5.3.12)
  - Locking symfony/routing (v5.3.11)
  - Locking symfony/service-contracts (v2.5.0)
  - Locking symfony/string (v5.3.10)
  - Locking symfony/translation (v5.3.11)
  - Locking symfony/translation-contracts (v2.5.0)
  - Locking symfony/var-dumper (v5.3.11)
  - Locking theseer/tokenizer (1.2.1)
  - Locking tijsverkoyen/css-to-inline-styles (2.2.3)
  - Locking vlucas/phpdotenv (v5.4.0)
  - Locking voku/portable-ascii (1.5.6)
  - Locking webmozart/assert (1.10.0)
Writing lock file
Installing dependencies from lock file (including require-dev)
Package operations: 111 installs, 0 updates, 0 removals
  - Downloading doctrine/inflector (2.0.4)
  - Downloading doctrine/lexer (1.2.1)
  - Downloading symfony/polyfill-ctype (v1.23.0)
  - Downloading webmozart/assert (1.10.0)
  - Downloading dragonmantank/cron-expression (v3.1.0)
  - Downloading symfony/polyfill-php80 (v1.23.1)
  - Downloading symfony/polyfill-mbstring (v1.23.1)
  - Downloading symfony/var-dumper (v5.3.11)
  - Downloading symfony/polyfill-intl-normalizer (v1.23.0)
  - Downloading symfony/polyfill-intl-grapheme (v1.23.1)
  - Downloading symfony/string (v5.3.10)
  - Downloading symfony/deprecation-contracts (v2.5.0)
  - Downloading psr/container (1.1.2)
  - Downloading symfony/service-contracts (v2.5.0)
  - Downloading symfony/polyfill-php73 (v1.23.0)
  - Downloading symfony/console (v5.3.11)
  - Downloading psr/log (2.0.0)
  - Downloading monolog/monolog (2.3.5)
  - Downloading voku/portable-ascii (1.5.6)
  - Downloading phpoption/phpoption (1.8.0)
  - Downloading graham-campbell/result-type (v1.0.4)
  - Downloading vlucas/phpdotenv (v5.4.0)
  - Downloading symfony/css-selector (v5.3.4)
  - Downloading tijsverkoyen/css-to-inline-styles (2.2.3)
  - Downloading symfony/routing (v5.3.11)
  - Downloading symfony/process (v5.3.12)
  - Downloading symfony/polyfill-php72 (v1.23.0)
  - Downloading symfony/polyfill-intl-idn (v1.23.0)
  - Downloading symfony/mime (v5.3.11)
  - Downloading symfony/http-foundation (v5.3.11)
  - Downloading symfony/http-client-contracts (v2.5.0)
  - Downloading psr/event-dispatcher (1.0.0)
  - Downloading symfony/event-dispatcher-contracts (v2.5.0)
  - Downloading symfony/event-dispatcher (v5.3.11)
  - Downloading symfony/error-handler (v5.3.11)
  - Downloading symfony/http-kernel (v5.3.12)
  - Downloading symfony/finder (v5.3.7)
  - Downloading symfony/polyfill-iconv (v1.23.0)
  - Downloading egulias/email-validator (2.1.25)
  - Downloading swiftmailer/swiftmailer (v6.3.0)
  - Downloading symfony/polyfill-php81 (v1.23.0)
  - Downloading ramsey/collection (1.2.2)
  - Downloading brick/math (0.9.3)
  - Downloading ramsey/uuid (4.2.3)
  - Downloading psr/simple-cache (1.0.1)
  - Downloading opis/closure (3.6.2)
  - Downloading symfony/translation-contracts (v2.5.0)
  - Downloading symfony/translation (v5.3.11)
  - Downloading nesbot/carbon (2.54.0)
  - Downloading league/mime-type-detection (1.9.0)
  - Downloading league/flysystem (1.1.7)
  - Downloading nette/utils (v3.2.6)
  - Downloading nette/schema (v1.2.2)
  - Downloading dflydev/dot-access-data (v3.0.1)
  - Downloading league/config (v1.1.1)
  - Downloading league/commonmark (2.0.2)
  - Downloading laravel/serializable-closure (v1.0.4)
  - Downloading laravel/framework (v8.73.2)
  - Downloading facade/ignition-contracts (1.0.2)
  - Downloading facade/flare-client-php (1.9.1)
  - Downloading facade/ignition (2.17.1)
  - Downloading fakerphp/faker (v1.16.0)
  - Downloading asm89/stack-cors (v2.0.3)
  - Downloading fruitcake/laravel-cors (v2.0.4)
  - Downloading psr/http-message (1.0.1)
  - Downloading psr/http-client (1.0.1)
  - Downloading ralouphie/getallheaders (3.0.3)
  - Downloading psr/http-factory (1.0.1)
  - Downloading guzzlehttp/psr7 (2.1.0)
  - Downloading guzzlehttp/promises (1.5.1)
  - Downloading guzzlehttp/guzzle (7.4.0)
  - Downloading laravel/sail (v1.12.6)
  - Downloading laravel/sanctum (v2.12.2)
  - Downloading nikic/php-parser (v4.13.1)
  - Downloading psy/psysh (v0.10.11)
  - Downloading laravel/tinker (v2.6.2)
  - Downloading hamcrest/hamcrest-php (v2.0.1)
  - Downloading mockery/mockery (1.4.4)
  - Downloading filp/whoops (2.14.4)
  - Downloading nunomaduro/collision (v5.10.0)
  - Downloading phpdocumentor/reflection-common (2.2.0)
  - Downloading phpdocumentor/type-resolver (1.5.1)
  - Downloading phpdocumentor/reflection-docblock (5.3.0)
  - Downloading sebastian/version (3.0.2)
  - Downloading sebastian/type (2.3.4)
  - Downloading sebastian/resource-operations (3.0.3)
  - Downloading sebastian/recursion-context (4.0.4)
  - Downloading sebastian/object-reflector (2.0.4)
  - Downloading sebastian/object-enumerator (4.0.4)
  - Downloading sebastian/global-state (5.0.3)
  - Downloading sebastian/exporter (4.0.4)
  - Downloading sebastian/environment (5.1.3)
  - Downloading sebastian/diff (4.0.4)
  - Downloading sebastian/comparator (4.0.6)
  - Downloading sebastian/code-unit (1.0.8)
  - Downloading sebastian/cli-parser (1.0.1)
  - Downloading phpunit/php-timer (5.0.3)
  - Downloading phpunit/php-text-template (2.0.4)
  - Downloading phpunit/php-invoker (3.1.1)
  - Downloading phpunit/php-file-iterator (3.0.5)
  - Downloading theseer/tokenizer (1.2.1)
  - Downloading sebastian/lines-of-code (1.0.3)
  - Downloading sebastian/complexity (2.0.2)
  - Downloading sebastian/code-unit-reverse-lookup (2.0.3)
  - Downloading phpunit/php-code-coverage (9.2.9)
  - Downloading doctrine/instantiator (1.4.0)
  - Downloading phpspec/prophecy (1.14.0)
  - Downloading phar-io/version (3.1.0)
  - Downloading phar-io/manifest (2.0.3)
  - Downloading myclabs/deep-copy (1.10.2)
  - Downloading phpunit/phpunit (9.5.10)
  - Installing doctrine/inflector (2.0.4): Extracting archive
  - Installing doctrine/lexer (1.2.1): Extracting archive
  - Installing symfony/polyfill-ctype (v1.23.0): Extracting archive
  - Installing webmozart/assert (1.10.0): Extracting archive
  - Installing dragonmantank/cron-expression (v3.1.0): Extracting archive
  - Installing symfony/polyfill-php80 (v1.23.1): Extracting archive
  - Installing symfony/polyfill-mbstring (v1.23.1): Extracting archive
  - Installing symfony/var-dumper (v5.3.11): Extracting archive
  - Installing symfony/polyfill-intl-normalizer (v1.23.0): Extracting archive
  - Installing symfony/polyfill-intl-grapheme (v1.23.1): Extracting archive
  - Installing symfony/string (v5.3.10): Extracting archive
  - Installing symfony/deprecation-contracts (v2.5.0): Extracting archive
  - Installing psr/container (1.1.2): Extracting archive
  - Installing symfony/service-contracts (v2.5.0): Extracting archive
  - Installing symfony/polyfill-php73 (v1.23.0): Extracting archive
  - Installing symfony/console (v5.3.11): Extracting archive
  - Installing psr/log (2.0.0): Extracting archive
  - Installing monolog/monolog (2.3.5): Extracting archive
  - Installing voku/portable-ascii (1.5.6): Extracting archive
  - Installing phpoption/phpoption (1.8.0): Extracting archive
  - Installing graham-campbell/result-type (v1.0.4): Extracting archive
  - Installing vlucas/phpdotenv (v5.4.0): Extracting archive
  - Installing symfony/css-selector (v5.3.4): Extracting archive
  - Installing tijsverkoyen/css-to-inline-styles (2.2.3): Extracting archive
  - Installing symfony/routing (v5.3.11): Extracting archive
  - Installing symfony/process (v5.3.12): Extracting archive
  - Installing symfony/polyfill-php72 (v1.23.0): Extracting archive
  - Installing symfony/polyfill-intl-idn (v1.23.0): Extracting archive
  - Installing symfony/mime (v5.3.11): Extracting archive
  - Installing symfony/http-foundation (v5.3.11): Extracting archive
  - Installing symfony/http-client-contracts (v2.5.0): Extracting archive
  - Installing psr/event-dispatcher (1.0.0): Extracting archive
  - Installing symfony/event-dispatcher-contracts (v2.5.0): Extracting archive
  - Installing symfony/event-dispatcher (v5.3.11): Extracting archive
  - Installing symfony/error-handler (v5.3.11): Extracting archive
  - Installing symfony/http-kernel (v5.3.12): Extracting archive
  - Installing symfony/finder (v5.3.7): Extracting archive
  - Installing symfony/polyfill-iconv (v1.23.0): Extracting archive
  - Installing egulias/email-validator (2.1.25): Extracting archive
  - Installing swiftmailer/swiftmailer (v6.3.0): Extracting archive
  - Installing symfony/polyfill-php81 (v1.23.0): Extracting archive
  - Installing ramsey/collection (1.2.2): Extracting archive
  - Installing brick/math (0.9.3): Extracting archive
  - Installing ramsey/uuid (4.2.3): Extracting archive
  - Installing psr/simple-cache (1.0.1): Extracting archive
  - Installing opis/closure (3.6.2): Extracting archive
  - Installing symfony/translation-contracts (v2.5.0): Extracting archive
  - Installing symfony/translation (v5.3.11): Extracting archive
  - Installing nesbot/carbon (2.54.0): Extracting archive
  - Installing league/mime-type-detection (1.9.0): Extracting archive
  - Installing league/flysystem (1.1.7): Extracting archive
  - Installing nette/utils (v3.2.6): Extracting archive
  - Installing nette/schema (v1.2.2): Extracting archive
  - Installing dflydev/dot-access-data (v3.0.1): Extracting archive
  - Installing league/config (v1.1.1): Extracting archive
  - Installing league/commonmark (2.0.2): Extracting archive
  - Installing laravel/serializable-closure (v1.0.4): Extracting archive
  - Installing laravel/framework (v8.73.2): Extracting archive
  - Installing facade/ignition-contracts (1.0.2): Extracting archive
  - Installing facade/flare-client-php (1.9.1): Extracting archive
  - Installing facade/ignition (2.17.1): Extracting archive
  - Installing fakerphp/faker (v1.16.0): Extracting archive
  - Installing asm89/stack-cors (v2.0.3): Extracting archive
  - Installing fruitcake/laravel-cors (v2.0.4): Extracting archive
  - Installing psr/http-message (1.0.1): Extracting archive
  - Installing psr/http-client (1.0.1): Extracting archive
  - Installing ralouphie/getallheaders (3.0.3): Extracting archive
  - Installing psr/http-factory (1.0.1): Extracting archive
  - Installing guzzlehttp/psr7 (2.1.0): Extracting archive
  - Installing guzzlehttp/promises (1.5.1): Extracting archive
  - Installing guzzlehttp/guzzle (7.4.0): Extracting archive
  - Installing laravel/sail (v1.12.6): Extracting archive
  - Installing laravel/sanctum (v2.12.2): Extracting archive
  - Installing nikic/php-parser (v4.13.1): Extracting archive
  - Installing psy/psysh (v0.10.11): Extracting archive
  - Installing laravel/tinker (v2.6.2): Extracting archive
  - Installing hamcrest/hamcrest-php (v2.0.1): Extracting archive
  - Installing mockery/mockery (1.4.4): Extracting archive
  - Installing filp/whoops (2.14.4): Extracting archive
  - Installing nunomaduro/collision (v5.10.0): Extracting archive
  - Installing phpdocumentor/reflection-common (2.2.0): Extracting archive
  - Installing phpdocumentor/type-resolver (1.5.1): Extracting archive
  - Installing phpdocumentor/reflection-docblock (5.3.0): Extracting archive
  - Installing sebastian/version (3.0.2): Extracting archive
  - Installing sebastian/type (2.3.4): Extracting archive
  - Installing sebastian/resource-operations (3.0.3): Extracting archive
  - Installing sebastian/recursion-context (4.0.4): Extracting archive
  - Installing sebastian/object-reflector (2.0.4): Extracting archive
  - Installing sebastian/object-enumerator (4.0.4): Extracting archive
  - Installing sebastian/global-state (5.0.3): Extracting archive
  - Installing sebastian/exporter (4.0.4): Extracting archive
  - Installing sebastian/environment (5.1.3): Extracting archive
  - Installing sebastian/diff (4.0.4): Extracting archive
  - Installing sebastian/comparator (4.0.6): Extracting archive
  - Installing sebastian/code-unit (1.0.8): Extracting archive
  - Installing sebastian/cli-parser (1.0.1): Extracting archive
  - Installing phpunit/php-timer (5.0.3): Extracting archive
  - Installing phpunit/php-text-template (2.0.4): Extracting archive
  - Installing phpunit/php-invoker (3.1.1): Extracting archive
  - Installing phpunit/php-file-iterator (3.0.5): Extracting archive
  - Installing theseer/tokenizer (1.2.1): Extracting archive
  - Installing sebastian/lines-of-code (1.0.3): Extracting archive
  - Installing sebastian/complexity (2.0.2): Extracting archive
  - Installing sebastian/code-unit-reverse-lookup (2.0.3): Extracting archive
  - Installing phpunit/php-code-coverage (9.2.9): Extracting archive
  - Installing doctrine/instantiator (1.4.0): Extracting archive
  - Installing phpspec/prophecy (1.14.0): Extracting archive
  - Installing phar-io/version (3.1.0): Extracting archive
  - Installing phar-io/manifest (2.0.3): Extracting archive
  - Installing myclabs/deep-copy (1.10.2): Extracting archive
  - Installing phpunit/phpunit (9.5.10): Extracting archive
83 package suggestions were added by new dependencies, use `composer suggest` to see details.
Package swiftmailer/swiftmailer is abandoned, you should avoid using it. Use symfony/mailer instead.
Generating optimized autoload files
> Illuminate\Foundation\ComposerScripts::postAutoloadDump
> @php artisan package:discover --ansi
Discovered Package: facade/ignition
Discovered Package: fruitcake/laravel-cors
Discovered Package: laravel/sail
Discovered Package: laravel/sanctum
Discovered Package: laravel/tinker
Discovered Package: nesbot/carbon
Discovered Package: nunomaduro/collision
Package manifest generated successfully.
78 packages you are using are looking for funding.
Use the `composer fund` command to find out more!
> @php artisan vendor:publish --tag=laravel-assets --ansi
No publishable resources for tag [laravel-assets].
Publishing complete.
> @php artisan key:generate --ansi
Application key set successfully.

NUC@NUC_LAB1 MINGW64 ~/Desktop
$ cd example-app

NUC@NUC_LAB1 MINGW64 ~/Desktop/example-app
$
