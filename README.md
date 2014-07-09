#Landy

**A flexible one-page fully responsive HTML template for your app**

This documentation will guide you through the basic functions of the template. Although the template is designed for a maximum ease of use, this guide it is not intended to teach HTML or CSS and you will require basic knowledge of both in order to customize the template to your liking.

<a href="http://landy.paolotripodi.com" target="blank" alt="landy-demo">Check out live demo here</a>

##Features

- Built on Bootstrap 3
- Fully Responsive
- Retina Ready
- Parallax Scroll
- CSS3 Animations
- Google Web Fonts

##Contents
1. HTML files
2. CSS files
3. Javascript files
4. Adding your screens
5. Using the icon set

##1. HTML files

The template has one HTML page where all the content for the site is housed:

```
index.html
```
The template is built upon the Bootstrap 3 framework (getbootstrap.com) and you have access to all the features of it. This means that you can use the 12 column grid like so:

```
<div class=”row”>
   <div class=”col-md-6”>
   ...
   </div>
   <div class=”col-md-6”>
   ...
   </div> 
</div>
```

The above code would give you 2 columns that sit side-byside on the page, each taking up half the page.

##2. CSS files

The theme has various CSS ﬁles, many of which you probably wont touch, but here is an overview of each one:

**iconfont.css** - This ﬁle controls the styling for the icon pack,donʼt worry about editing this, you will style your icons individually in the style.css ﬁle

**bootstrap.min.css** - This is the css framework provided by Bootstrap and includes the basic styling for the page (grid etc) and all the styles related to the framework itself. You probably wont need to touch this.

**animate.min.css** - This includes the styling of the Daniel Edenʼs CSS3 
animation library Animate.css. Animations are triggered via Javascript in the 
scripts.js ﬁle.

**style.css** - This is the main style ﬁle that includes the styling for all the visual 
elements in the template. This is the one you will likely edit when you want to 
make adjustments (remember to use the Chrome inspector, it will tell you 
which line of css to edit and in which ﬁle!)

##3. Javascript Files
As with the CSS ﬁles, you probably wont edit most of the Javascript ﬁles. Here is an overview:

**jquery.js** - The most famous and widespread Javascript library. You wont need to make adjustments to this ﬁle

**retina.min.js** - The javascript to serve high-resolution images to devices with retina displays. To provide the retina version of a an image, create an image twice the size of the original, and then just add @2x to the same ﬁle name as shown below:

```
logo.png
logo@2x.png
```

**bootstrap.min.js** - The javascript provided by Bootstrap as part of the framework.

**animatescroll.js** - Provides smooth scrolling, to smooth-scroll to an element inside the page just use

```
<a onclick="$('[id-or-class-of-element]').animatescroll();">Go to Element</a>
```

**scripts.js** - This ﬁle is the main scripts ﬁle that controls all the pretty features of the template such as the the CSS3 animations. It also controls the mobile menu toggle and slider initializations.

##4. Adding your screens

Adding your app screenshots to the template is as easy as so: just replace the images in the img/screenshots folder with yours, keep the same ﬁle name and youʼre done! Images will appear in all the templateʼs carousels.

##5. Using the Icon Set

This is a relatively simple process but you must be sure to include a few important things:

1. Open icons-reference.html inside the icon-font folder
2. You will see a list of available icons, followed by their character mapping

Use this code:

```
<div class="icon-x" ></div>
```

(where X is the iconʼs name)

For example, for the facebook icon, you would do this:

```
<div class="icon-facebook"></div>
```
##Copyright and Licensing

Code and documentation © Paolo Tripodi, 2014. 
Code released under <a href="https://github.com/paolotripodi/Landy-v1.0/blob/master/LICENSE.md" alt="MIT Lincense">MIT</a>

<hr/>

Checkout Lady on <a href="http://drbl.in/kbfC" alt="Dribbble - Landy">Dribbble</a> and <a href="http://bit.ly/1nU1DLF" alt="Dribbble - Landy">Behance.</a>

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/paolotripodi/landy-v1.0/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
