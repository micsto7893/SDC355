# SDC355 Portfolio

## What Is This?
This is my portfolio page for SDC355 at ECPI University.
It started as a simple class project and, like most coding projects, slowly grew extra features whether I asked for them or not.
The page includes an About section, a Projects section, Featured Content, dark mode, a contact form, and some JavaScript that does more work behind the scenes than the page probably deserves.

## What I Used
This project uses:
- HTML5
- CSS3
- JavaScript
- JSON
- DOM Manipulation
- Session Storage
- Local Storage
- Git
- GitHub

## How the Projects Work
The Projects section is built using JavaScript objects.

Each project stores:
- Project Title
- Brief Summary
- Image URL
- Repository or Project Link

The project objects are placed into an array. That array is converted into a string using:
`JSON.stringify()`

It is then saved in session storage using:
`sessionStorage.setItem()`

When the page loads, JavaScript checks to see if the project data is already sitting in session storage.
If it is not there, the project array gets stored.
If it is already there, the data is pulled back out and converted into usable JavaScript with:
`JSON.parse()`

The projects are then created dynamically using DOM manipulation instead of being hard-coded directly into the HTML.
Basically, JavaScript builds the project section so I do not have to manually write the same HTML over and over again.

## Dependencies
There really are not many.
You need:
- A modern web browser
- JavaScript enabled
- The ability to open an HTML file without angering your computer

Browsers that should work just fine include:
- Pick one, there are many and they all work.

## How to Run It
1. Download or clone the project files.
2. Keep `index.html` and `README.md` in the project folder.
3. Open `index.html` in a web browser.
4. Admire the very serious academic portfolio.
5. Click around and make sure nothing catches fire.

The project information should load automatically when the page opens.

## Current Projects
The portfolio currently includes:
1. StopPoint
2. Vigilant Waffle
3. Hello World

More projects can be added later by creating another JavaScript object and adding it to the project array.
In theory, this makes future updates easier.
In practice, future me will probably still stare at the code for ten minutes trying to remember what past me was doing.

## Author
Michael Stoller
ECPI University  
SDC355
