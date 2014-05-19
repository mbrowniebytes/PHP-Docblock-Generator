PHP-Docblock-Generator
======================
Generate PHP Docblock placeholders for files/folders.


usage
========
> php docblock.php file|folder [-r] [targetFunction]

|                 |                                                         |
------------------|----------------------------------------------------------
| file or folder  | the file or folder you want to docblock (php files)     |
| -r              | optional, recursively go through a folder               |
| targetFunction  | optional, docblock only a specific method/function name |

Examples:

> php docblock.php target.php targetFunction

> php docblock.php target/dir -r


change log
========
* **2014-05-19 version 0.86**
* Replaced hard coded \n with option $newline
* Added option $add_anonymous to add Dockblocks for anonymous functions
* Added option $add_full to add all or minimal Docblock params
* Added $description_placeholder to add (or ignore) a default description
* Add the number of Dockblocks created to log
* If no Dockblocks created, added log entry "Nothing to Doc Block"
* Preserve tab indentations when adding Docblocks
* Catch some undefined index errors

* **2010-06-16 version 0.85**
* https://github.com/agentile/PHP-Docblock-Generator


license
========
http://opensource.org/licenses/MIT


