# horiseon-hw
Refactoring Horiseon webpage for accessibility

In refactoring the html and css for the Horiseon webpage I started at the top and addressed the html first. 

The main html items addressd were:
* Creating semantic html tags to replace the <div> tags
* Updating the links so they all worked (one needed an id added)
* Adding titles to links and alt to photos
* Removing superfluous items (the content in the main three sections had both id's and classes however they worked without the addition of a class and could be grabbed by css by their article section tags)
* I added comments at the start of each main grouping of content 


The css items updated included:
* reorganizing the css flow to follow the html flow or elements
* Consolidating elements which shared the exact same css by grabbing them through parent tags (i.e. h2 rather than having three separate 'section h3 .<id name>{}' that all have the same css)


