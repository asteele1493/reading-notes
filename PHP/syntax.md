# PHP Syntax

Opening and closing tags:

```php 
<?php echo 'This is how you use PHP code in XML. By using these tags.'

?>
```

To note: If the file you're working in only contains PHP, it's preferable to omit the closing tag.

If youre file has mixed content, meaning HTML mixed with PHP for example, as long as the HTML is outside of the PHP tags will be ignored by the PHP parser. 

An example using conditions:

```php
<?php if ($expression == true): ?>
This will show if the expression is true.
<?php else: ?>
Otherwise this will show.
<?php endif; ?>
```

A semicolon designates the end of a statement. A closing PHP tag implies a semicolon, even if it's not listed. 

One-line comment: ```//```

Multi-line comment:```/*    */```

Built-in types within PHP include: 
- null
- boolean
- integer
- float
- string
- array
- object
- callable
- resource