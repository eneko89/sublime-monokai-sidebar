### sublime-monokai-sidebar

Sublime Text is great, but it's sidebar doesn't match the default (and beautiful) dark Monokai theme. Thanks to [this gist](https://gist.github.com/umpirsky/5842174) and after tweaking it a little (I corrected a glitch with the code collapse icon and made the higlight color lighter), I finally made it look great:

![Picture](https://coderwall-assets-0.s3.amazonaws.com/uploads/picture/file/3441/sublime2.png)

### Installation via Terminal
**macOS:**
```
cd sublime-monokai-sidebar/
```
```
mkdir /Users/$USER/Library/Application\ Support/Sublime\ Text\ 3/Packages/Theme 
```
```
mv Default.sublime-theme /Users/$USER/Library/Application\ Support/Sublime\ Text\ 3/Packages/Theme/
```
**Linux:**
```
cd sublime-monokai-sidebar/
```
```
mkdir /home/$USER/.config/sublime-text-3/Packages/Theme
```
```
mv Default.sublime-theme /home/$USER/.config/sublime-text-3/Packages/Theme
```

### Installation using other methods
**Windows (File Explorer):** 

Copy file to user directory here:
```
%userprofile%\AppData\Roaming\Sublime Text 3\Packages\User\Theme
```

**Using Sublime Text 3:**

Press `ctl + shift + p` or `shift + cmd + p` to open Command Palette, type `Browse Packages` and hit enter. In that folder, create a `Theme` directory and place the `Default.sublime-theme` file.
