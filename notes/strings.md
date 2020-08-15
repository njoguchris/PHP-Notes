# Strings

## Working with text

> As seen in the first chapter, a string is a group of characters created by surrounding text in single or double quotes.
```php
<?php

$firstname = 'John';
$lastname = "Ndungu";
```

> A double quoted string can interpret special characters starting with a back slash to create formatting. The `\n` creates a newline between the names and after them.
```php
echo "Jacob\nJuma\n";
```

> Double quoted strings can also embed variables in the text. > This code outputs "Cindy Mrem".
```php
$firstname = 'Cindy';
echo "$firstname "Mrem \n";
```

> Another feature of strings is the ability to combine them together.

> To combine two strings, use the period character in between them.
```php
$firstname = 'Jenny';
$lastname = 'Madison';
$fullname = $firstname . $lastname;
echo $fullname;
```

[ Previous Lesson - PHP Arithmetic ](./arithmetic.md) 

[ Next Lesson - PHP Comparisons ](./arithmetic.md)
