# keywordhunter
A python script to loop through urls in a csv and look for specific keywords on the scraped homepage.


This specific example opens a familyoffice.csv stored in the same folder,
scrapes the homepage and cleans it up using Beautiful Soup (i.e. removes HTML),
and then searched for the keywords VC and Venture Capital.

It was originally set up to save a new csv when loop was complete,
but added functionality to add csv during loop (in case the loop errored out, etc.).
Currently this last part is not working and keywords are not being saved.
