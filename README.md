# PHP-GTK3-RPGET
A Tool to encrypt Files in PHP-GTK3

## HOWTO

Just download and run the "rpget_neu.exe" and you will see this:

![grafik](https://github.com/subabrain/PHP-GTK3-RPGET/assets/7425736/eef5db88-275b-45cb-b9ac-131f75008602)

Now you have to do the follwoing:

1. For Path to PHP Folder use the PHP Folder from here: https://github.com/subabrain/PHP-GTK3-Encrypt
2. Choose the Path to your Folder where the PHP-GTK 3 Files are in
3. Then choose a Folder where your ready App is stored
4. Now Choose the Files you want to encrypt - you can add multiple Files here - just select them in the Folder Window

####  Important - the PHP-GTK 3 Sourcecode has to be without the PHP Brackets!

5. At Last choose a Key for encryption - it has to be 16 Chars long

Now Press "Encrypt Files!".

Go to your created output Folder and navigate to "phpgtk" and run the Command:

.\..\php\php.exe "your_php_file.php"

Important: in the "your_php_file.php" you have to set the

```
<?php

  encrypted_file("encrypted_phpgtk3_file");

?>
```
To your with this Tool encrypted Files ... thats all ;)

### Congratulations now you created a encrypted PHP-GTK 3 Application!
