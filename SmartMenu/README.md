# Smart Menu
![img](https://i.imgur.com/eQYWK2a.gif)

### About
This is a stylized animated Menu system with automatic Page indexing for you Blazor Project.

### RoadMap

- [x] Basic Style and theme
- [x] Automatic "search" and show buttons for each routable razor component
- [x] Support custom images and text for each button in menu screen
- [ ] Add search functionality 
- [ ] Add minimized version (currently it's only full screen)
- [ ] (Optional) add favourites and show them first

### How to add it to your project

Basically the project searches all razor components for the variables below , and gets their default values

```public const string MenuIcon ;```

```public const string MenuTitle ;```

So each of your pages should contain those two constants.

Assuming that ,  
put the line below to your MainLayout component

`<FullScreen @ref="FullScreen" />`

Having the reference in your project you can call the function `FullScreen.Toggle();` to show the menu 

Enjoy
