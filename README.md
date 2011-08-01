If you are a WordPress theme developer and you love code automatization (like me) then this is certainly something for you!  

I've created lots of WordPress themes in the past and it's always been a hassle to fully optimize a theme and make it independent for every platform. Besides, you really don't want to get bothered with things like minification, optimization, compressing etc. Wouldn't it be great to get a wonderful default theme that solves all of this? 

### HTML5 Boilerplate
That's why I love HTML5 Boilerplate, it's written by Paul Irish (also known as the developer of jQuery and so on..)! Maybe you are familiar with it, but if not you should definitely check it out and give it a try. It does all the magic for you without having to write any extra code! It's basically a default HTML5 setup that handles minification, optimization etc, but it's much more then that.. see http://html5boilerplate.com

### Compass CSS
What HTML5 Boilerplate is for HTML is Compass Style for CSS. Well, obviously that isn't completely true.. but anyway you'll get the point. Compass gives you more control in structuring your CSS in a fashion manner. And the great thing, like HTML5 Boilerplate it's free and open-source! One of the benefits is that you can use variables, mixed-in functions and lots more, for more info check http://compass-style.org/  

# Default Wordpress Theme  
Having that said, this default WordPress theme provides a solid foundation where these two great innovations comes together! You can use Compass CSS in conjunction with the great build script of HTML5 Boilerplate right out of the box.


# How to get it up and running?
+ Clone/download this github repo in your theme
+ Edit the WordPress template files to your needs (header.php, footer.php, index.php etc)
+ Apply your CSS styles in sass/_mytheme.scss (if you'd like another name make sure you edit the reference in _boilerplate.scss on line 77).
+ Use Compass watching/compiling to generate a valid css file in css/style.css
+ Publish your theme using the HTML5 Boilerplate build script.

Don't forget to check the WIKI pages..

## Sidenote
The build folder of the HTML5 Boilerplate framework which I use in this theme, is slightly modified in order to make it work with WordPress template files. These are just minor modifications, but it's good to mention these changes, so you are aware of it. Don't just copy/paste another build folder inside your theme. If you do so, errors may occur when running the ant build script. Updates of newer versions of the HTML5 Boilerplate script will be updated automatically in this default theme when available.