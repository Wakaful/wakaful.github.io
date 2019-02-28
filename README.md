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

-----

##### Blog Posts

The blog is manual. You first need to copy one of the folders inside the `blog` folder where the name of that folder will be the blog URL so must be all lower case without spaces. Once you have a new folder you then need to update the `index.html` contained inside that folder with the following check list:

1. Page title (line 9)
2. FB Meta (lines 17 to 23)
3. Blog title and date
4. Blog content
5. Social media links
6. Social media titles

If you want the blog preview to show up on the main `wakaful/blog` page, you will need to manually add it by updating the main `blog/index.html`.