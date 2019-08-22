# Sublime Settings and Snippets
This includes common snippets as well as my syntax specific settings for sublime text 3.


### Create Symlink
removes your existing `User` directory for sublime text 3 and replaces it with this repo.
```
rm -rf ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User; ln -nfs ~/sublime/ ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
```

### CLI support for sublime
ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/sublime