# Transfer Tasks

- [🏠 Home](../index.md)
- [💪 SW06 - Errors & Error Management](../SW06%20-%20Errors%20&%20Errors-Mgmt.md)

## Error origin
Discuss where in your product which errors can occur. Name at least 3 locations and show the types of defects.

1. Profile > Account > Delete account: A user might accidentaly delete their account if the button is placed elsewhere
2. Profile > Account > Delete account: A user might accidentaly delete their account if no confirmation prompt is shown
3. Favourites: A user might accidentaly remove a recipe / event from his favourites

## Error prevention
Build 3 specific defect prevention strategies into your product that reference Part 1: Error origin.

1. Place the button in a remote location
2. Add a confirmation prompt where you have to type the username
3. Add an undo action when removing a favourite

## Dealing with errors
Discuss where you cannot necessarily avoid mistakes and offer the opportunity to undo the mistake, offer help or allow the mistake to be 'fixed'.

- After having cooked a recipe, the user might want to rate it, but if he clicks away too quickly, he has to find the recipe again in order to rate it. This is not a huge deal because this problem is compensated with the absence of a rate button on hte bottom of each recipe, which would be superfleous; Not many user would indeed use it.