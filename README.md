# Fallen Sanctum event list enhancements
Enhancements for Fallen Sanctum event list page.

## What does this script do?
* In the [Fallen Sanctum event list page](https://www.fallen-sanctum.com/manual.php?p=events), this script highlights the events you are able to do.
    * If the event is up to 5 levels below your skill, it's highlighted in green.
    * If the event is lower than 5 levels below your skill, blue.
    * If the event is 1 level above your skill, yellow.
* Your current skill level is shown at the end of the event text, with a link to the skill manual page.

## How to use
1. [Click here to install](https://github.com/dang-nabbit/fs-event-enhancements/raw/master/fs-event-enhancements.user.js) (or open the `fs-event-enhancements.user.js` and click the "Raw" button at top right).
1. Edit the installed script.
1. Copy your skill list from the game and replace line breaks with the "pipe" character (`|`).
The result should look like this: `Woodcutting: 34 (1,360,155 XP)|Construction: 31 (943,442 XP)|Mining: 19 (133,481 XP)|Gathering: 18 (128,851 XP)...`.
1. Paste the skill list with pipes in script on [line `15`](https://github.com/dang-nabbit/fs-event-enhancements/blob/master/fs-event-enhancements.user.js#15), inside the single quotes, replacing the previous skill list.
1. Save the script and open the [Fallen Sanctum event list page](https://www.fallen-sanctum.com/manual.php?p=events).
