# Application Name

#### Brief description of application, 7/22/20

#### By Cody Fritz, Thomas Glenn, Alison Sadin

## Description

## Languages & Technologies Used:

### Programming Languages & Libraries

- Bootstrap
- CSS
- HTML
- JavaScript
- jQuery
- Node
- WebPack

### Operating Systems & Programs

- Git Bash
- Google Chrome
- Microsoft Windows 10
- Visual Studio Code

## Installation

1.  Download a web browser, such as Apple Safari, Brave, Google Chrome, Microsoft Edge, Mozilla Firefox, or Yandex.
2.  Navigate to [repository].
3.  Click the green "Clone or download" button at the right of the screen.
4.  Select "Download ZIP."
5.  Use a file extractor or unzip program (such as PeaZip, Unzipper, WinZip, Zipware, or 7-ZIP) to extract the ZIP files onto your computer.
6.  Open the directory containing the extracted files.
7.  Open your computer's terminal and navigate to the directory bearing the name of the program and containing the top level subdirectories and files.
8.  Enter the command "\$ npm install" in the terminal and press "Enter".
9.  Follow the "Instructions for Obtaining an API Key" section below to obtain your unique API key for [API(s)].
10. Enter the command "\$ npm run build" in the terminal and press "Enter".
11. Enter the command "\$ npm run start" in the terminal and press "Enter".
12. The program should open and run with its user interface accessible in your default web browser.

### Instructions for Obtaining an API Key

    1.  Download a web browser, such as Apple Safari, Brave, Google Chrome, Microsoft Edge, Mozilla Firefox, or Yandex.
    2.  Navigate to [API webpage].
    3.  Click the button to sign up for a new account or sign in to your existing account.
    4.  Navigate to the section of the API webpage that contains your API key.
    5.  Copy your API key.
    6.  Return to your cloned or downloaded copy of the program you are setting up and open the terminal.
    7.  Make sure you have entered the root menu of the program directory.
    8.  Enter "$ touch .env" into the terminal.
    9.  Open the .env file you have just created and type "API_KEY = " into the file.
    10. Paste your copied API key into the .env file directly after "API_KEY = ".
    11. Review any JavaScript files (*i.e.*, those ending in ".js") in the src subdirectory of the program directory for API calls from the API from which you have obtained the key.
    12. In any of the API calls, identify the section of the API URL that contains the sequence "appid=[API-KEY-GOES-HERE]".
    13. Replace "[API-KEY-GOES-HERE]" with "${process.env.API_KEY}".
    14. Make sure all files in the program directory and subdirectories are saved.
    15. Repeat this process for any other APIs that are called in the program.

## Known Bugs

No known bugs!

## Support and contact details

For support please contact | 

## Technologies Used

HTML | C# | dotnet framework

### License

MIT

Copyright (c) 2020 **Allison Sadin**
