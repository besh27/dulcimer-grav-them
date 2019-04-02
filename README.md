# dulcimer-grav-them
------------------------
## A GRAV CMS theme created for the Dulcimer Hymnal

##Creating a Backup

Backing up your project is nothing more than creating an archive of the ROOT of Grav. No Database, no complications.

Of course you can simplify this even more by just using the Grav CLI. Supposing we have our ~/workspace/portfolio project and that we want to create a backup of it, here's what we will do:

$ cd ~/workspace/portfolio
$ bin/grav backup

------------------------

## Backing up and Uploading Themes

Backing up and uploading your themes is nothing more than navigating to user/themes/ and copying your current theme and renaming it with symanitic versioning (example theme_v1.0.0). Next, Open the renamed theme directory and find the php and yaml files that share the same name as your theme. Add the symantic version number to those files as well. After that, zip the entire theme directory folder. 

Open a browser and navigate to the admin side of your grav site (example gravsite.com/admin). Click on the "Tools" navigation button on the bottom left. Next, click the "choose file" under the "install a zip package by uploading" header. Find your file and upload it. 

Next, navigate to the themes admin page by clicking the "Themes" button on the bottom left navigation button. Find the theme you previously uploaded and click to active it. That's it!

-----------------------

## Activating /  Deactivating plugins

Navigate to the Plugins page by clicking the navigation link on the left side of the admin panel. Find the plugin that you want to activate or deactivate and click the toggle button in the same row. Done. 

-----------------------

## Add New Pages

Click the Add button at the top right corner of the admin panel. 

Add a Page Title (the Folder Name is auto populated) and then choose if the page will have a parent page or not. 
Choose "Default" for the Page Template. 
Next, Click "Yes" for visible.
Last, click "Continue".

-----------------------

## Edit a Page

Use markdown to add content to the page. 
A great resource for markdown is https://daringfireball.net/projects/markdown/syntax. Check it out!

To add code to the content section of a page you will need to use a bit of HTML, but it's easy.
simply place "<pre class="prettify">" before the code content and "</pre>" after the code content. 

Example:
<pre class="prettify">
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "dev": "ts-node ./src/server.ts",
    "start": "babel-node index.js"
  },
</pre>

-----------------------

More additions to the document will come in the future.

- contact beshdevelopment@gmail.com for any questions.
