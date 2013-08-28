smid·gen
================================
_noun informal_
a small amount of something.

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
