TaskList
========

This is just a practice situation I've set up for myself. There is a .NET tutorial on the web, a recent one, that has a zip file called ToDo.zip, or TaskList.zip-something like that, and it's a PHP app created in WebMatrix. But, WebMatrix PHP apps still use the web.config for db connections and uses other misc. references in order for it to run in IIS/WebMatrix.
I will take a go at removing any dependencies as well as moving the db conn strings into a PHP config file. Will also remove any ADO.NET specific code within the project and PHP-ify it.
