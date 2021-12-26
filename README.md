# [HTML and CSS](https://lmberard.github.io/HTML_CSS/)

### **Just for testing purposes: CSS Basics, flexbox, grids, animations, etc...**

It is made with SASS.
In order to use SASS I installed the Live Sass Compiler extension in VsCode.
In the HTML file there should be the link for the css file that the compiler creates, not the scss.

Basically SASS is useful for:

- having "variables" or constants.
- you can nest properties and "include" them in "one box of something particular". For example:

```scss
div {
  font{
    decoration: xxx ;
    transform: xxx;
    align: xxx ;
    etc..
    }
}
```

- you can modularize the files and include them.
  In order to do that you have to name the file with a "\_" at the beginning of the file name so it does not get compiled and them import it.
- you can also create "functions" or groups/structures of styles called Mixin
