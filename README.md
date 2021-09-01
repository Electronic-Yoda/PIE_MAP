![wideBG](https://user-images.githubusercontent.com/83682911/131602318-140a58d3-aead-448e-a32a-3c14120a7b1b.png)
# PIE_MAP
PIE_MAP is a C++ mapping application allowing users to view, search, and interact with 19 major cities around the world. Designed for tourists in mind, PIE_MAP's GUI ensures fewer clicks can do more. It's vibrant colors and theme based on WCAG Contrast Guidelines allow for a great visual experience.

Since some of the project are a part of the university's course work, many files in PIE_MAP are kept private on GitHub. This repository is meant to demonstrate PIE_MAP's functionality with gifs and photos. Additionally, it stores PIE_MAP's user interface and its relevant files, which are a deviation from the course and are meant to greatly expand PIE_MAP's user experience.

PIE_MAP is co-developed by Raymond Yang (https://github.com/Electronic-Yoda), Stephen Wang (https://github.com/Stephenwang3801), and David Tran (https://github.com/davidtran001). 
It depends on the ezgl graphics library https://github.com/mariobadr/ezgl, the GTK library, and data in OpenStreetMap. 

##  Direction search with keyboard input. 
- Rather than relying on GTK widgets, the entirety of PIE_MAP's direction UI panel, including the searchbar and dropdown lists, are rendered directly on canvas for a maximum visual experience.
![directionSearchDemo](https://user-images.githubusercontent.com/83682911/131556822-f00dc2c3-176e-4af3-baab-fcf0858ea44a.gif)

## Direction search by map-clicking
- Seamlessly switch from keyboard input to map-clicking if necessary. There is great user flexibility.
![directionClickDemo](https://user-images.githubusercontent.com/83682911/131544710-124dc925-d471-421c-a030-11d368217312.gif)

## View maps around the world
- There are nineteen maps to explore across the world, ranging from Tokyo to Moscow.
![changeMap](https://user-images.githubusercontent.com/83682911/131564900-36bd6012-f45c-48a2-a6d4-235acb9082f6.png)

## Find Mode
- Search for intersections and points of interests, and PIE_MAP locate and will pan in on the area.
![changeMap2](https://user-images.githubusercontent.com/83682911/131602731-27f357d1-9057-40c8-a3b2-86fbaf95bc9b.png)
![find](https://user-images.githubusercontent.com/83682911/131563107-28ec23ba-f44e-4045-9aa0-7b6a65dfded0.png)

## PIE_MAP_UI is the main user interface for PIE_MAP
PIE_MAP_UI is used to render searchbars and dropdown lists of the program directly on canvas. The development of this UI became necessary when we realized the GTK library and its widgets were very limiting in terms of color selection, placement, and were unable to satisfy our goal of providing great visuals and usability. 

The following features are avaliable in PIE_MAP_UI:
- A Generate Buttons Algorithm
- A Namespace for the direction-finding user interface
- A Searchbar generator
- Generation of drop down lists for searchbars
- Data structures and functions/methods enabling program reactions to user input (mouse, keyboard)
- Drawing major components of the UI on canvas

