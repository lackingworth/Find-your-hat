# Find your hat

Easy Terminal game, where the player must navigate to the goal

## Rules

You control a player represented by ``` * ``` symbol. 



You must navigate through the game field while avoiding holes represented by ```O``` symbol using the folowing inputs:

```U``` to go ```Up```, ```D``` to go ```Down```, ```L``` to go ```Left``` and ```R``` to go ```Right```

The game ends when player is:

1. Out of bounce (beyond the playing field)
2. Fell into the hole (```*``` overlapped with ```O``` symbol)
3. Reached the goal (represented by a ```^``` symbol)

## Getting Started

### Installing

* To play this for yourself you must have an up-to-date [Node.js](https://nodejs.org/en/download) installed on your system
* This game works on any terminal of your choosing, but for the best experience I recommend using [Git.Bash](https://git-scm.com/downloads)

### Executing program

* Clone this repository to the location of your choosing
* Open your terminal
* Navigate to the saved location using ```cd folderName``` command, where *folderName* is the name of your path folder
* When in right location run:
```
node main.js
```

## Help

If the game froze or your inputs are not registered correctly press ```Ctrl + C``` to stop the application

Feel free to report any issues or suggest improvements

## Version History

* v.0.0.1:

    * Initial Release

## Acknowledgments

Application was created from Codecademy's challenge project:

* [Codecademy](Codecademy.com)
* [Codecademy Back-End Engineer Career Path](https://www.codecademy.com/career-journey/back-end-engineer)
