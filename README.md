# This Project contains two parts - UI created through WPF and API calls code written in C#.
The UI is a WPF App which contains two forms MainWindow and SunInfo.
MainWindow form will polulate with content using xkcd comic Api call. It consist of previous and next buttons to navigate to different comic pages.
SunInfo form will populate info about Sunrise and Sunset times for the given location using Sunrise-Sunset.org Api.

# How to download and setup local environment to start project.
Download zip file from Github Code dropdown and try opening it after extracting the file. It should open in Visual Studio.
Build the project to get all the dependencies in your local environment as necessary.
Hit Ctrl+F5 to run/start the Web App or click Start from the top navigation panel.
On App start it should load current comic on the MainWindow form with option to go and look other comic pages using previous and next button.
When Sun Information Button on MainWindow is clicked it should take you to SunInfo page.
Click Load Sun Info button to display the Sunrise and Sunset times for the location.
