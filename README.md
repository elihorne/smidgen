smid·gen
================================
_noun informal_  
a small amount of something.

The goal of smidgen is to quickly generate the bare minimum amount of HTML, CSS, and JavaScript to get a prototype up and running. You probably have your own definition of "bare minimum", but this is mine. 

You get the HTML5 doctype, latest version of jQuery, empty placeholders to your own style.css and function.js and an init function at the bottom that lets you know things are working (check the console).  

Just a smidgen to delete, and the rest is yours. 

Usage
-----

Add this to your .profile, .bashrc, _.whatever_

```
smidgen(){
        git clone http://github.com/elihorne/smidgen.git $1
        cd $1 && open .
}
```

Then navigate to your project directory and type:
```
smidgen [your project name]
```

Voila. Just enough to get you moving.
