# PHP-recap
Genopfriskning på PHP fra S1

- PHP afvikles fra en PHP-server
  - Web-server
  - Lokalt installeret server som XAMPP, WAMP, MAMP eller lignende
  - En docker container
  - Kan også afvikles i en terminal, hvis man har et PHP-CLI
- PHP skrives i filer, der ender på .php
- PHP skrives i en PHP-kodeblok: <?php ?>
- PHP-kode bliver afviklet på serveren og sender så resultatet, af den kode man har lavet, tilbage til clienten

## PHP-kode
```
/* PHP-kommentar */

/* Variabel */
$name = "John Doe";

/* Konstant */
define( "MY_FULL_NAME", "John Doe" );

echo constant( "MY_FULL_NAME" );

/* Function */
function printName( $name ) {
    echo $name;
}

printName( "John Doe" );

/* If */
if( true ) {
    echo "This is true";
} elseif ( true ) {
    echo "Then this is true";
} else {
    echo "Else this is true";
}
```