## Mapping Sinclair Broadcast's reach

These files and folders are meant to accompany [a walkthrough](http://r-journalism.com/posts/2018-07-17-sf-sinclair-map/map/) on [r-journalism.com](https://r-journalism.com).

The quickest way to access the data for this chapter is to 1) make sure your current project directory is logically organized. 

Hopefully, you've created folder on your computer in your `Documents` folder called `r-journalism` or something like that.

Once you've set your working directory (with maybe `setwd()`) then you can run these commands in your console to download the correct folders and data:

```
install.packages("usethis")
```

and then

```
usethis::use_course("https://github.com/r-journalism/sf-sinclair-map/archive/master.zip")
```

----

Otherwise:

Clone or download and unzip this repo. Make sure the folder is **not** in a temporary unzipped folder.

To ensure these files work as expected, please make sure the project directory is set up correctly: 

When you type `getwd()` it should look something like `your_file_path/sf-sinclair-map`

You can manually set this up by:

*Session > Set Working Directory > To Project Directory*

Alternatively, you can double click the **sf-sinclair-map.Rproj** file from your finder/file browser.

----

Navigate to the .rmd files for each sub-chapter to open and follow along with each section.

Or you can execute the following commands in the console to bring up the files.

* `file.edit("map.Rmd")`

To view the local html version of the .rmd files, you can try the following commands in your console to see rendered version of the sub-chapter:

* `browseURL("map.html")`

----
