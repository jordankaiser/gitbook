# Creating a new View

To create a new view to to _Structure &gt; Views &gt; Add View_. Under View Settings you'll get a drop-down for Show. This drop-down lists all the different types of Entities which can display Views. Choose the appropriate Type and sorting. Content is probably what you want. By choosing Content what you're doing is saying, hey Drupal, create a list of every piece of Content on the site that is of type XYZ.

Then on Page Settings you can create a page that will house the content created by this view. Below that you can have this view by setup as a Block too. Setting it up as a block will allow the list of content created by this view to be usable whereever on the site. So you could put it in a sidebar for example. Under Display format HTML list is good for displaying the list as html content.

When setting up the criteria for a view it's important to note the Display types at the top \(Page, Feed, Block etc\). The point here is that each Display type can have different criteria applied to it. For example while it would make sense to have a pager on the Page display of a View it might not make sense to have a pager on the Block display.

