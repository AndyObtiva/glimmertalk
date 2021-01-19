# Glimmertalk
Ruby low-effort interactive GUI app development environment akin to Smalltalk, written in Glimmer (Ruby Desktop Development GUI Library) 

## Background

Building GUI with Glimmer GUI DSL syntax is great. It is certainly lighter and quicker than using complex WYSIWYG editors.

That said, there is still value in inspect live application GUI directly instead of going back to the code and relaunching the app on every code change.

One idea is to use a special shortcut (or glimmer command arg) that enables Glimmertalk. 
What that does is enabling a new menu to show up when right-clicking on any widget in a running desktop application.
This Glimmertalk menu has a menu item that opens up a code text editor showing the code behind any visible widget, 
so the developer could edit on the spot, save, and Glimmertalk takes care of refreshing the GUI automatically.
In the future this could grow with more menu items that enable tweaking properties live in a standard table-based property editor, and then spit out a code chunk out of it with all the changes.
This should provide great productivity benefits and be faster than the typical inspectors you see in browsers that overwhelm the user by showing all the code at once
instead of only showing the code of the widgets we are concerned about.

In the future, Glimmertalk could be integrated directly into Gladiator (or any editor for that matter) to enable more convenient editing of Glimmer application GUI.
