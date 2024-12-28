# Game Manager - Executable Library
The Game Manager is a simple desktop application built using PySimpleGUI that allows users to manage their executable files (EXE files) and associated assets. It provides a user-friendly interface for adding games, playing them, and performing Google searches, all from within one application.

### Features
Upload: Easily upload and add new games(dosnt need to be a game) by providing the executable path and asset folder path.
Google Search: Perform Google searches from within the application.
Time Display: Displays the current date and time.
Help Section: Provides guidance on how to use the application.
Installation 

### Adding a Game
In the "Upload Your Executable" section, fill in the following fields:

Game Name: Enter the name of your game.
Executable Path: Browse to the EXE file you want to add.
Assets Folder Path: Browse to the folder containing assets related to the game.
Click "Add Game" to add the game to the Library.

### Playing a Game or lauching ExE file
After adding a game, the name of the game will appear in the Library section.
To play the game, select the game from the list and click "Play Game".

### Searching on Google
In the Google Search section, type your query into the input field.
Click the "Search" button to perform the search.

### Help Section
To view the help instructions, click on the Help menu in the menu bar and select Help.
The help section will provide a step-by-step guide on how to use the application.

### Removing a Game
To remove a game, simply delete the associated JSON file in the storage directory.
The game will no longer appear in the Library section.
