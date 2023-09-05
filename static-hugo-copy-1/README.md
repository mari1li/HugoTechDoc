1/ If we want to change the Demo Hugo menu, we go to head.html (themes/layout/partials/head.html)

2/ If we want to change side bar menu, we go to themes/layout/partials/sidebar.html

3/ If we want to add a new page in the menu,

we can add a .md file in the /content directory with this head format 

+++
title = "Team Member"
date = "2014-04-09"
menu = "main"
+++

4/ if we want to change the sidebar menu from open or slide, we can go to the hugo.toml, in the [params]
# for the menu to be wide open, we use "open-menu",
# if we want to drop down the menu, we use "slide-menu"
menu_style = "slide-menu"