# DeigHtml2
This is a new clone to cover the changes made in the last few years.

This is the core Deig website witten with html, css, and bootstrap.

This is a rewrite based on the [DowneastIntergroup](https://github.com/wcswanson/Intergroup). 

Thses files show a few changes  from [aa-deig.org](https://github.com/wcswanson/DeigHtml).

The original site was written with html. A separate file contained the files written for devices.  
The new site use the Liquid Web Template which reads the browser size and reformates the page for  
that browser. After template was used, the Bootstrap menu was added. Bootstrap includes the tools   
needed for browser displays. 

This website is being hosted on a linux box using a Apache web server.  
The meeting list was moved off of the linux box to a Windows host so Sql Server 
can be used to maintain and display the database. This was done before Microsoft   
started working on Core. 

The new meeting list display can be found in the repository for wcswanson.

This website uses SSI (server side includes) to simplify the menu and footers.  
If the menu needs to be modified, it can be updated in on place and it will be shown  
on all the pages on the website.

An Apache server will need to be used to properly display this website in test.
