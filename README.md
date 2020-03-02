// the first thing I noticed when doing this was that the footer and header were both using div tags.
both the header and footer can use their own respective tags to make things more clear for the dev. Having 
a massive list of div after div is not easy to navigate and look at in the HTML file even when the sections are 
given classes. I feel like this helps clean it up and switched the footer div tag to a footer tag as well as changing 
the header section into a nav tag because the header of this site is used for navigating the contents of the page.

// next I worked on the dead link for "search engine optimization" Both of the other links in the nav bar take you to 
a new location in the page but search engine optimization doesn't do anything when you click on it. While trying to 
figure out why the other two links worked but this one didnt have any action when clicked, I noticed that the other two
had ID tags inside their divs. adding the id to the search engine optimization div section was the key to making this 
class work. 

// The meta data of "website" was changed to a more appropriate title of "Horiseon Home"

//next i moved all of my work into my personal repo from the class repo. after moving the html, css,
and img files i had to change the file path for the images in the code to show up. because i was not working 
in the same folder i had to get the images into my new folder then direct the paths to the images without the 
'assets' folder.

// 