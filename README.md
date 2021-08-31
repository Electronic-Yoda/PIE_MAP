# PIE_MAP
PIE_MAP is a C++ mapping application allowing users to view, search, and interact with 19 major cities around the world. Designed for tourists in mind, PIE_MAP's GUI ensures fewer clicks can do more. It's vibrant colors and theme based on WCAG Contrast Guidelines allow for a great visual experience.

Since some of the project are a part of the university's course work, many files in PIE_MAP are kept private on GitHub. This repository is meant to demonstrate PIE_MAP's functionality with gifs and photos. Additionally, it stores PIE_MAP's user interface and its relevant files, which are a deviation from the course and are meant to greatly expand PIE_MAP's user experience.

PIE_MAP is co-developed by Raymond Yang (https://github.com/Electronic-Yoda), Stephen Wang (https://github.com/Stephenwang3801), and David Tran (https://github.com/davidtran001). 
It depends on the ezgl graphics library https://github.com/mariobadr/ezgl, the GTK library, and data in OpenStreetMap. 

##  Direction search with keyboard input. 
- Rather than relying on GTK widgets, the entirety of the direction UI panel, including the searchbar and dropdown lists, are rendered directly on canvas for a maximum visual experience.
![directionSearchDemo](https://user-images.githubusercontent.com/83682911/131556822-f00dc2c3-176e-4af3-baab-fcf0858ea44a.gif)

## Direction search by map-clicking
- Seamlessly switch from keyboard input to map-clicking if necessary. There is great user flexibility.
![directionClickDemo](https://user-images.githubusercontent.com/83682911/131544710-124dc925-d471-421c-a030-11d368217312.gif)

## View to maps around the world
- There are 19 maps to explore
![changeMap](https://user-images.githubusercontent.com/83682911/131561876-fbc1ef5d-d2b2-4ec6-b2eb-f40e85ea7581.png)


PIE_MAP_UI is the main user interface for PIE_MAP. The following features are avaliable in PIE_MAP_UI:
- A Generate Buttons Algorithm
- A Namespace for the direction-finding user interface
- A Searchbar generator
- Generation of drop down lists for searchbars
- Data structures and functions/methods enabling program reactions to user input (mouse, keyboard)
- Drawing major components of the UI on canvas

