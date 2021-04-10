# simple-dash

Try the Demo here: https://zerdion.github.io/simple-dash/

A simple, fully responsive Dashboard to forward to the services of your choice! Ideal for Desktop and mobile usage!
Add all of your services, whether you host them yourself or not and display them as neat Icons from the Font Awesome library.
simple-dash is made to be as simple and minimalistic as possible. (The goal was to create a dashboard even my mom could use!) :)
Based on: https://github.com/thetomester13/homepage

This project uses:
- Material Design Icons
- Trianglify

This is a fork by @zeridon with several improvements over @swagielka's original version:

 - Static background support
 - Icon image URL support
 - [TOML](https://github.com/toml-lang/toml) configuration file
 - Removed excess horizontal space on pages with small numbers of icons

## To Use
1. Clone this repository with git.
2. Copy the `config.sample.toml` file to `config.toml`. Update the fields as appropriate to configure your homepage.
3. Open `index.html` in your browser!

## Configure Homepage
- 'items' => The menu will scale to the amount of items you want to display. Insert any link you'd like, or {{cur}} for the current URL of the page. Choose icons from [Font Awesome](http://fontawesome.io/icons/)
