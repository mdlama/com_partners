This is a component for the Partners page of QUBES.
=======================================================

This component will mimic the structure and admin editing style of the com_drwho component example from hubzero at:
https://hubzero.org/documentation/2.1.0/webdevs/components .
If you are reading this and comparing this and the drwho component, you will find many similarites, however you will not find an API controller.
This is because the API controller is not necessary to the component, and was just provided as a example.
	See for yourself by deleting the api folder!
    
========================================================
@author Jacob Harless jrharless@email.wm.edu

Installation
============

When downloaded as a ZIP file from http://hubzero.org/documentation/2.0.0/webdevs/components
unzip and place the resulting directory into /app/components

The final result should look like:

    /app
    .. /components
    .. .. /com_partners
    .. .. .. /admin
    .. .. .. ../controllers
    .. .. .. ../help
    .. .. .. ../language
    .. .. .. ../views
    .. .. .. ..partners.php
    .. .. .. /config
    .. .. .. /helpers
    .. .. .. /models
    .. .. .. /site
    .. .. .. ../assets
    .. .. .. ../controllers
    .. .. .. ../language
    .. .. .. ../views
    .. .. .. install.sql
    .. .. .. partners.xml

The install.sql file contains SQL for creating the needed database tables and populating them
with sample data. This may be manually added to the database or installed via the "discover"
feature of the extensions manager:

Login to the administrator area. Go to "Extensions > Extensions Manager". Click the sub-menu
item "Discover". From that page, click "Discover" in the toolbar. If you see "Dr Who" show up
in the resulting list, click the checkbox next to it and click the "Install" button.