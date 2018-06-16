modify package for better viewing:
============
preferences - java - appearence - check abbrivation package names [package name = [demo]] - apply

import & export collection of plugin and share across the colligs:
=======================
import - Install - from existing installation - select - plugin path 
export - Install - Installed s/w items to file - browse - eclipse.p2f - check eclipse git team provider

In-place outline (ctrl + f3)(ctrl+t)
================
-select out line of the class
-select any class and press (ctrl + f3) then u can see out line of that class
-Type hyrarchy
-press (ctrl + f3) twice it will show inhirate members also.
-(ctrl+o)

Hovers:
========
window - preferences -java - editors - check expand verticle ruler icons
ctrl + shift + hover -> show java doc view (also see java doc tab for documentation)
shift + hover -> show source code(declaration tab to see source code)


BookMark ur code: for future reference:
========================================
-Right click on left roler select Add bookmark -give name to it (shown book mark icon ) check bookmark tab for all bookmarks.

Make check list to do today check list:
========================================

Show annotation for author of particular line of code or modified code.
-right click on left roler and select Show annotation.
-and then reght click on  left roler select Revision - show Id(have multiple options).
-hover on particular annotation u can see commiting of that code details.

***
Block selection mode:
Alt+shift+a and select the ex private or particular code and modify it.(default behaviour)

override default behaviour :
===================
Ctrl+space (give suggestions) then press ctrl it will show yellow coller to override the existing code after the cursor.
Preferences - java - Editor - content assist - select radio button (Completion overwrites)

Templates for easy development:
==========================
eg:
 main, foreach syso
For create our own template ;
================
Quick access - search (templates) - we can edit tempates or create new templates - 
preferences - java - editor - templates - u can do export and import templates. 

Formatters:
=============
prferences - serch for formatter -edit - off/on tabs and check enable off/on tabs so format the before and ofter the comments.

Debugging:
===========
-Smart step intoselection.
-Step filter.
-Grouping break points.
-Print points.:
===========
 Print points does not stop ur execution it prints the sysout on console.
 It is usefull when u debug race condition or threads.
 line breakpoint - check conditional check Suspent when true and write sysop and always return false at end of line.
 
 
 Lambda Expressions:
 ====================
 convert to normal code to lambda expressions.
 select code that need to be convert( annonomous interface ) ctrl+1 and slect convert to lamda expression.
 then hover on -> (lambda expression ) u have some option like 
 -convert to methed reference( :: )
 -change body expression back to block.
 -convert to anonymouse class creation.
 -Extract to local varioble.
 -Extract to local variable.
 
 To know UI plug in Implimentation in eclipse:
 ======================
 alt+shift+f1 opens (Plug-in selection spy) then u can see all the plugin related to that UI:
