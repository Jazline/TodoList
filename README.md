We are creating a Day scheduler
First of all I started by creating a html file in which I made two divs, one for the header and one for the spaces were my text areas would be.
Then I divided each text area by sections,each section had a class and an id, as well as a button.
Then I linked my moment js link to the script tag and created a function which displays the day.(from lines 88 to 98).
After that I made an onclick function (lines 102-107) which saves whatever value in the text area to the local storage using set item.
Since I wanted the value to still be displayed after the page was refreshed , I created another function (lines 110-122).With jquery I selected my id and class and set the value to retrieve whatever was stored in that text area from local storage.
The next step was to compare the actual time of the day to the time of the event on the planner..
