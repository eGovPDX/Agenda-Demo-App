#Agenda Demo App

##What
This is a simple app showing what you can do with the PDXCouncilConnect API. This app loads up an agenda via the API, loops through the sessions looking for items, adds the items to a list, and allows commenting on individual agenda items for council members or other citizens to then reply or read.

##Install

The app is a simple `index.html` file that contains HTML/CSS/JS and uses the API, jQuery, and Disqus. To only installation is that you need a Disqus account at: [http://disqus.com/]() and need to create a new site at: [http://disqus.com/admin/register/]() then update the shortname at the line that currently says `var disqus_shortname = 'pdxcouncilagenda';` with your shortname you created in the 3rd step during the site signup.