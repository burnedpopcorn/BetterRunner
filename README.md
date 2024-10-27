# BetterRunner
A replacement for runner.html (GX.GAMES Test Output) with many New Features

GameMaker Version Used: ```2023.2```

Other GameMaker Versions might work, but Newer Versions might not display the "Downloading Data" Loading Bar

> [!NOTE]
> This uses my Pizza Tower 1.1.0 Web Port as the Base, so the website's Title and Github Repo will all reflect that
>
> Also, this will work out-of-the-box with any GMS2 Project compiled to GX.GAMES Export (as a VM Test Run), but if you compile it as a YYC Test Run, you will have to change functions ```manifestFiles()``` and ```manifestFilesMD5()``` to be the same as the YYC runner.html

## Context
runner.html is a file that runs a GameMaker Studio 2 project that was compiled for GX.GAMES as a Test Run, and is compiled along with the project files when compiling a test run, but runner.html is very basic and has ussless functions, and that brings us to betterrunner.html

## About
betterrunner.html does everything that runner.html does, but strips away Useless Functionality and adds many New Features, and those changes include:

### Game Loading
betterrunner.html now displays loading progress after Downloading Game Data, mainly for bigger projects that take time to load

### Button Changes
1. Main Buttons have been Increased from 3 to 6
2. A Green Dashed Border has been added to the buttons, and button text is now White
3. All Buttons now have a Description when Hovering over them

New Buttons:
- ```Toggle Console```: Toggles Console, which Lists Game Information such as Loading and Internal Game Debug Strings ( from show_debug_message() )
- ```Visit Github Repo```: (Mainly for Me) Opens New Tab to Redirect to My Pizza Tower Noise Update Github Repository
- ```Clear Site Cache```: Clears IndexedDB Files, which is needed to fix crashes that appear when Website is Updated (Also Reloads all Included Files and Deletes Saves)
- ```Enable FPS Counter```: Enables FPS Counter Bookmarklet (Click on FPS Window to Cycle through other Functions of the Bookmarklet)
- ```View All Web Ports```: (Mainly for Me) Opens New Tab to Redirect to My Personal Webpage with a List to all of my Web Ports
- ```Join Discord Server```:(Mainly for Me) Opens New Tab to Redirect to My Discord Server

### Background Color Changer
There is now a Background Color Changer that changes the Background of the Website to Any Color you wish

Default Background Color is Black

Background also is no longer a Radial Gradient, but instead a Solid Color of your choice

### Better Favicon Support
If ```favicon.png``` is available and in the same folder as betterrunner.html, then it will be used as the Website's Icon

And that's all
> [!WARNING]
> Mobile was NOT considered during the making of betterrunner.html and will probably not work with this file
>
> Ads were also not considered, but weren't modified either, so they might be broken
