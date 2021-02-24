# emailValidationPhpUnit
Email Validation using PHP Unit for testing

Pre-requisitos tener instalado composer



# Despues de descargar este proyecto ejecutar el siguiente comando para instalar dependencias
composer require --dev phpunit/phpunit ^9.5

# Desde la terminal, ejecutar el siguiente comando (PhpUnit Test)
%root-folder-your-project%\vendor\bin\phpunit tests

# Salida de la terminal (PhpUnit Test)
PHPUnit 9.5.0 by Sebastian Bergmann and contributors.

...                                                                 3 / 3 (100%)

Time: 00:00.140, Memory: 4.00 MB

OK (3 tests, 3 assertions)


# Desde la terminal, ejecutar el siguiente comando (PhpUnit TestDox Test)
%root-folder-your-project%\vendor\bin\phpunit --testdox tests

# Salida de la terminal (PhpUnit TestDox Test)
PHPUnit 9.5.0 by Sebastian Bergmann and contributors.

Email
 ✔ Can be created from valid email address
 ✔ Cannot be created from invalid email address
 ✔ Can be used as string

Time: 00:00.110, Memory: 4.00 MB

OK (3 tests, 3 assertions)


