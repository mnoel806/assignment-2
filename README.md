# assignment-2

### THE GENERAL PLAN

<MAKE IT WORK, THEN MAKE IT PRETTY>

- Make basic html skeleton
- use VERY simple names
- Use common prog terms like FETCH POPULATE & DISPLAY
-    Not ambiguious terms like getThat loadList & showStuff
-    I'll get less lost
- Screw being fancy. If you need to code something repeatitively, just do it for now. You can be optimized fater it works


# OVERVIEW

This repo contains a lot of labour to make a webpage that satisfies enough requirements to pass the web2 COMP 3512 criteria. Asked for help some Web Friends to have an idea of a plan


## Features

- A Season Selector which loads a list of Races in a Selector.
- Race Selector will be unhiden and offer a specific selection of races.
- Once a race is selected, the qualifying results and race results sections will be unhidden and the data will display.
- If user clicks on a driver's name (.driver.Forename+Surname), a modal will open and display all the relevant data
    about this specific driver
- If user clicks on a constructors's name (.constructor.name), a modal will open and display all the relevant data about the constructor (THIS MEANS CAR BUILDERS NOT THE RACE OR AN OBJECT CONSTRUCTOR)
    about this specific driver
- If user clicks on the circuit's name (race.circuit?), a modal will open and display all the relevant data
    about this specific circuit



## Technologies Used
- HTML, CSS, JAVASCRIPT, CHATGPT
- Chatgpt was used to generate css to help visualize the page I was working on. Being able to see things happen while I am testing something I can't see is SUCH a help


## Project Files
- index.html - Home Page
- coding.js - accompanying JS code file
- mattington.css - stylesheet
- What to do.md - A working file that things got dumped into, erased, reworked, and times when I wanted to yell at the computer to 'just work'T

## API Routes

- api/f1/results.php + ?season=XXX: Returns all race info for specific season
- api/f1/qualifying.php + ?raceID=XXX: Returns all qualifying results info for specific race
- api/f1/races.php + ?raceID=XXX: Returns all race results info for specific race
- ~~api/f1/circuits.php~~
- ~~api/f1/constructors.php~~
- ~~api/f1/drivers.php~~
