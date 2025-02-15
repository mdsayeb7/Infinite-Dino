# Dino-Bot

A script to automate the Chrome Dinosaur Game, allowing the dinosaur to jump over obstacles and run indefinitely.

## Description

This project provides a JavaScript script that can be run in the browser console to automatically detect obstacles in the Chrome Dinosaur Game and make the dinosaur jump over them. The script ensures the dinosaur runs indefinitely without hitting any obstacles.

## Usage

### Step 1: Open the Chrome Dinosaur Game

Open the Chrome browser and go to `chrome://dino` to start the game. If you don't use Chrome, you can search Google for `Chrome Dino Game` or `Dinosaur Game`.

### Step 2: Open the Developer Console

Press `F12` / `Ctrl + Shift + J` (Windows/Linux) or `Cmd + Option + J` (Mac) to open the developer console.


### Step 3: Paste the following code into the console and press Enter

```javascript
fetch('https://raw.githubusercontent.com/mdsayeb7/Dino-Bot/main/script.js')
    .then(res => res.text()).then(script => new Function(script)()); 
