# Sass example

#### Requirements:
⋅⋅* Install Ruby from website only for window and for mac it is builton [rubyinstaller.org](https://rubyinstaller.org/downloads/) 
And download through commandPrompt by typing **_gem install sass_**.
finally sass is installed if not then try **_sudo gem install sass_**.

next step is setup a watcher in sass folder **_sass --watch main.sass:main.css_** its looks great for me

### Different Tools to compile Sass

##### Manual way of compliling sass
which is in cmd **_sass app.sass app.css_** 
and another way is **_sass --watch main.sass:main.css_** for auto compile. 

great book for the advance way to write code 
here is the website link 
[smacss.com](https://smacss.com/)

### Sass partial example
    This way of making extension like **footer.sass** if we add **_footer.sass** it
    tell sass do not add this sass in our project with the hel of that you watch all sass folder and compile it into css folder
    and we don't want to change any import statement because sass is smart and he's knows what is partial sass which is **_footer.sass** and what a sass file is **footer.sass**.