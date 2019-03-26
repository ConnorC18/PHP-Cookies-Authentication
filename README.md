# PHP Cookies Authentication

## Installation

+ Download the PHP Cookies Authentication
+ Add to your project directory

## Usage

+ Go to the index.php file. It should look like this:
![index.php](http://i.imgur.com/sdnTG1l.png)

+ Open Inspect Elements and enter one of developer codes. By default these are *Name1-Password1* and *Name2-Password2*. Then refresh and you will be able to view the page! To 'LogOut' Just clear your cookies or remove the developer code you used from the list.!
![showcase.gif](https://i.ibb.co/ypsdX5p/Desktop2019032622025707-1.gif)

+ Built into the **index.php** is a password generator, thanks to <a href="https://www.phpjabbers.com/generate-a-random-password-with-php-php70.html">These Guys </a>, Using this you can generate passwords for the developer password for example you could use: YourName-*GeneratedPassword*
###### Examples
```PHP
// generate one password using 5 upper and lower case characters
randomPassword(5,1,"lower_case,upper_case");
 
// generate three passwords using 10 lower case characters and numbers
randomPassword(10,3,"lower_case,numbers");
 
// generate five passwords using 12 lower case and upper case characters, numbers and special symbols
randomPassword(12,5,"lower_case,upper_case,numbers,special_symbols");
```
You can read more about the password generator <a href="https://www.phpjabbers.com/generate-a-random-password-with-php-php70.html">Here </a>


## Coming Soon

+ Ability to make codes in the browser
+ Ability to remove codes in the browser
+ Button to clear cookie
