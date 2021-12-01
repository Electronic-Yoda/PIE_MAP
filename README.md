![wideBG](https://user-images.githubusercontent.com/83682911/131602318-140a58d3-aead-448e-a32a-3c14120a7b1b.png)
# PIE_MAP
PIE_MAP is a C++ mapping application allowing users to view, search, and interact with 19 major cities around the world. Designed for tourists in mind, PIE_MAP offers a vibrant color scheme and easy navigation.

Since some of the project are a part of the university's course work, many files in PIE_MAP are kept private on GitHub. This repository is meant to demonstrate PIE_MAP's functionality with gifs and photos. Additionally, it stores PIE_MAP's user interface and its relevant files, which are a deviation from the course requirements and are meant to greatly expand PIE_MAP's visuals.

PIE_MAP is co-developed by Raymond Yang (https://github.com/Electronic-Yoda), Stephen Wang (https://github.com/Stephenwang3801), and David Tran (https://github.com/davidtran001). 
It depends on the ezgl graphics library https://github.com/mariobadr/ezgl, the GTK library, and data in OpenStreetMap. 

##  Direction search with keyboard input. 
- Rather than relying on GTK widgets, the entirety of PIE_MAP's direction UI panel, including the searchbar and dropdown lists, are rendered directly on canvas for a maximum visual and user experience.
![directionSearchDemo](https://user-images.githubusercontent.com/83682911/131556822-f00dc2c3-176e-4af3-baab-fcf0858ea44a.gif)

## Direction search by map-clicking
- Seamlessly switch from keyboard input to map-clicking if necessary. There is high degree of user flexibility.
![directionClickDemo](https://user-images.githubusercontent.com/83682911/131544710-124dc925-d471-421c-a030-11d368217312.gif)

## View maps around the world
- There are nineteen maps to explore across the world, ranging from Tokyo to Moscow.
![changeMap](https://user-images.githubusercontent.com/83682911/131564900-36bd6012-f45c-48a2-a6d4-235acb9082f6.png)

## Find Mode
- Search for intersections and points of interests, and PIE_MAP locate and will pan in on the area.
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


# The Project
| Description | Image |
|-------------|-------|
| Logo and POI Pins | <img src="https://github.com/Stephenwang3801/PIE_MAP/blob/main/images/Logo.png?raw=true" width="300" height="300"> <img src="https://github.com/Stephenwang3801/PIE_MAP/blob/main/images/Pins.png?raw=true" width="465" height="155"> |
| Choosing screen for available cities | <img src="https://github.com/Stephenwang3801/PIE_MAP/blob/main/images/Available%20Cities.png?raw=true"> |
| Map Design | <img src="https://github.com/Stephenwang3801/PIE_MAP/blob/main/images/Map%20Design.png?raw=true"> |
| Search Functionality (GIF) | ![Alt Text](https://github.com/Stephenwang3801/PIE_MAP/blob/main/images/Search.gif?raw=true) |
| Map Layout with Panel | <img src="https://github.com/Stephenwang3801/PIE_MAP/blob/main/images/Map%20Layout%20With%20Panel.png?raw=true"> |
| Pathfinding Algorithm by using the search bar in the side panel (GIF) | <img src="https://github.com/Stephenwang3801/PIE_MAP/blob/main/images/Direction%20Algo%20Keyboard.gif?raw=true"> | 
| Pathfinding Algorithm by clicking on the map (GIF) | <img src="https://github.com/Stephenwang3801/PIE_MAP/blob/main/images/Direction%20Algo%20Clicking.gif?raw=true"> | 
| Courier Path with multiple destinations | <img src="https://github.com/Stephenwang3801/PIE_MAP/blob/main/images/Courier%20Path.png?raw=true"> | 
| Toronto | <img src="https://github.com/Stephenwang3801/PIE_MAP/blob/main/images/Toronto.png?raw=true"> | 
| Tokyo | <img src="https://github.com/Stephenwang3801/PIE_MAP/blob/main/images/Tokyo.png?raw=true"> | 
| London | <img src="https://github.com/Stephenwang3801/PIE_MAP/blob/main/images/London.png?raw=true"> | 
| New York | <img src="https://github.com/Stephenwang3801/PIE_MAP/blob/main/images/New%20York.png?raw=true"> | 
