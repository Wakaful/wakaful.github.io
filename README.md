### Basic Documentation

A collection of useful notes.

-----

#### GitHub via Mac Terminal

First need to navigate to folder.
Assuming you are using XAMPP - should be:

```
cd /Applications/XAMPP/xamppfiles/htdocs/something-something
```

The `ls` command lets you see current folder.

Assuming you are now in the website folder and have set your `remote` to `waka` - you can pull the latest version by:

```
git pull waka master
```

If you want to push changes made locally, you need to:

```
git add .
git commit -m "explain the update"
git push waka master
```
