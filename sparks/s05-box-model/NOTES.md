# NOTES — <assignment name>

## Intent
The page is a progress tracker for collection items in the animal crossings video game. In the game you can collect fish, bugs, art, and fossils until you complete each collection. The site should keep track of a users progress. For this site, create a mock user with a random collection. It's nav is uses by an animal crossings player who wants to view their different collections' progress.
Assume that the user navigating the page is a child who is not a strong reader. The theme is the Animal Crossings video game.

## AI use
I used the copilot chat to create the index.html and styles.css files for this spark. I gave it my intent and the done list and asked it to propose a plan for a new page that highlights the box model in it's design.

## Accepted / changed / rejected
I accepted the plan that it suggested for building the page. I ended up changing the page layout and how the content was arranged. Originally all of the collection types were in one section and I requested that each item type had it's own section with an associated button in the nav bar that takes you to that section. I did this to add more buttons to the nav bar so I could actually test the box model.

## Dig deeper
One thing I looked up (https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/Descendant_combinator) was the .nav-list a selector. I learned that that selects every <a> link inside of an element that has the nav-list class and so it knows what element to apply the space around. The selector is specifically a descendant selector because it combines two selectors, in this case those are the nav-list class and a!

## Open questions

