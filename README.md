Rainbou
=======

Simple color scheme file generator
----------------------------------

Rainbou takes two files: a color file and a template file. The color file contains color definitions, while the template file contains details about where to put the colors.

### Example:

#### Color file

```
$COLOR_0$ #000000
$COLOR_1$ #111111
...
$COLOR_15$ #ffffff
```

#### Template file

```
*.color0 $COLOR_0$
*.color1 $COLOR_1$
...
*.color15 $COLOR_15$
```

#### Result

```
*.color0 #000000
*.color1 #111111
...
```

For more examples, check out the color files and templates in this repo.
