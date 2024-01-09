# How to run locally

Prerequisites

+ Pull the submodule. Files will be placed in the `data` folder.
+ Swap to local Bootstrap by uncomment and comment style sheets in `index.html`.
+ Block comment the expression that assign an online URL to the `url` variable in `main.js`.
+ Please do not commit these changes back to the repository.

## Method 1: HTTP Server

Set up a HTTP file server.

## Method 2: Local File Access

*This method is not recommended because Chrome will show a warning heading.*

+ Launch Chrome with `--disable-web-security` argument, or uncomment it in `launch.json` if you use VSC.
+ Open `index.html` in Chrome.

# How to modify way points

Waypoints are hardcoded in the beginning of `main.js`.
Press `V` to print current camera location and rotation to console.

# How to maintain the code

This program is completed in a short period of time, thus it is not designed to be maintained.