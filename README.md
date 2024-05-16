#  Kingplouf - Toilet reign web application

![Logo](https://benoitbusnardo.fr/assets/images/projects/bonus/kingplouf/logo.png)


Welcome to Kingplouf, a web application to custom your toilet ambiance. It has music and can send colors to gpio's of an arduino system. The application is really simple but make a great job in entertaining. 


## Screenshots

![App Screenshot](https://benoitbusnardo.fr/assets/images/projects/bonus/kingplouf/screen.png)
![App Screenshot](https://benoitbusnardo.fr/assets/images/projects/bonus/kingplouf/screen2.png)
![App Screenshot](https://benoitbusnardo.fr/assets/images/projects/bonus/kingplouf/screen3.png)

## Demonstration

Here is the dispositive installed on a reel toilet with leds and speakers.

![App Screenshot](https://benoitbusnardo.fr/assets/images/projects/bonus/kingplouf/demo.png)
![App Screenshot](https://benoitbusnardo.fr/assets/images/projects/bonus/kingplouf/demo2.png)
![App Screenshot](https://benoitbusnardo.fr/assets/images/projects/bonus/kingplouf/demo3.png)

## Installation

You can run it without any arduino system. To configure gpio's just modify them inside :
functions/toggleTheme.php

For the colors, the system was made for leds with rgb value as 0 or 1. So each color variable is either a 0 or a 1.

To run Kingplouf app, you only need to run index.php.