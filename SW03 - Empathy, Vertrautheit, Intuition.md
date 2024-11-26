# SW03 Empathy, Vertrautheit, Intuition

[Learn Facts](LearnFacts/Learn%20Facts%20SW03.md)

[Transfer Task](TransferTasks/Transfer%20Task%20SW03.md)

## Scenario Persona

Annabella is feeling worn out after a long day of classes and her part-time job. She opens the MealBestie App, hoping to find something comforting and easy to make with the few ingredients she has left in her fridge. The app, tuned to her preferences and past choices, immediately suggests a few simple recipes that feel warm and satisfying.

As she reviews the suggestions, the app intuitively highlights meals that fit her dietary restrictions, reassuring her that every option is safe. She trusts the app completely, knowing it remembers her allergies and avoids anything that could cause a reaction. With a gentle nudge, MealBestie even suggests a calming tea recipe that pairs well with her meal—a thoughtful touch that shows it understands her mood.

Annabella wants to see only notifications, when someone answers to her question, she asked in the community. She doesn’t want other notifications from the app.

Annabella has specific dietary and food preferences, this is covered in the chapter on flexibility and efficiency.

## Comparing Other Apps

### Empathy

A good cooking apps must have good empathy to truly connect with users and support their needs. Empathy means understanding users’ unique lifestyles, dietary and food preferences, and offering options that make them feel cared for and understood. Apps must prioritise  features, like personalized recipe suggestions and gentle reminders for food restrictions. Apps can create an experience where users feel supported.

- CookPad
    - Understanding users unique lifestyle and recipe suggestions: Cookpad doesn’t have a suggestions page, relying only on recently searched recipes to understand user preferences. This approach limits personalisation and reduces the app’s ability to adapt to users’ tastes, or ingredient availability, making it feel less intuitive and engaging.
        
        ![Screenshot 2024-11-07 at 08.13.54.jpeg](sw03_3.jpeg)
        
    - Notifications: Cookpad sends notifications to keep users engaged by sharing seasonal recipes, cooking tips. Unfortunately, there is nothing personalized like notifications on past searches or cooked recipes. Cookpad also doesn’t have the option for users to adjust notification settings. The user is not in control over the frequency and types of alerts they receive. It either no or all notifications, this can also be set in the iOS or Android notification setting.
- Tasty
    - Understanding users unique lifestyle and recipe suggestions: Tasty includes a Discover page with recipe suggestions, providing a more personalized experience compared to basic search history. However, the basis for these suggestions is unclear, making it difficult for users to understand if recommendations are tailored to their tastes, dietary preferences, or ingredient availability. This lack of transparency can make the Discover page feel less intuitive, leaving users uncertain about how well the app truly understands their preferences.
        
        ![Screenshot 2024-11-07 at 08.15.41.jpeg](sw03_4.jpeg)
        
    - Notification: Like Cookpad, Tasty sends notifications to keep users engaged by sharing seasonal recipes, cooking tips. Unlike Cookpad the notifications are personalised on past searches or cooked recipes. Tasty doesn’t have the option for users to adjust notification in the settings. There is a button for notifications in the settings, but this button only forward's you to the notification settings of the Smartphone itself, where you can either allow all notifications or no notifications.

### Familiarity and Intuition

Apps can enhance user experience by building familiarity through intuitive design and consistent interactions. Familiar layouts help users feel comfortable and confident as they explore features. 

- CookPad
    - Intuitive Design: Annabella can easily filter which products she wants to have in her search and which she doesn't want to have. She can easily filter products by typing them into the text box. This is much more intuitive than selecting filters from a menu.
        
        ![Screenshot 2024-11-07 at 08.09.40.jpeg](sw03_2.jpeg)
        
    - Familiar layouts: Cookpad is very easy to use and has a lot of familiar elements in it. For example, the "Today's Popular Searches" feature is similar to the Spotify search feature, which offers a list of trending or frequently searched items. This layout makes navigation intuitive for users who are already accustomed to other popular platforms, adding a sense of familiarity and ease.
        
        ![Screenshot 2024-11-07 at 12.43.20.jpeg](sw03_5.jpeg)
        
- Tasty
    - Intuitive Design: When Annabella searches for something, she has some quick and popular options to choose from. Unfortunately, there is no filter option to filter out products or ingredients she doesn't want.
        
        ![IMG_2920.PNG](sw04_21.png)
        
    - Familiar layouts: The Discover feature provides a variety of recipe options that other app users have already tried. Annabella is familiar with this concept from Instagram, so she quickly realises she can scroll through and explore new recipes with ease. Unfortunately also there is no filtering option for things she doesn't want to see.
        
        ![IMG_2919.PNG](sw03_7.png)
        

| Scenario-part | Finding / Description | Garret-L / Severity | Proposal  |
| --- | --- | --- | --- |
| Browse recipes and get suggestions | Annabella wants to browse through recipes and get suggestions based on her preferences, the time and day of the week. On CookPad is no option to browse for recipes. On Tasty, there is a browse feature which has suggestions, but it is very intransparent  on what these suggestions are based. | Interaction Design 
/
Good  | Annabella wishes that she could browse through recipes and the app really understands her and her needs. She also wants transparent suggestions. |
| Notifications | Annabella wants to receive only notifications when someone replies to her community interactions. Annabella is not able to choose on what things she wants to get notifications. She can either decide if she wants all notifications or no notifications. | Interaction Design 
/
Good
 | Annabella wants to choose which notification she gets and which she don’t want to receive. |
| FIlter Recipes | Annabella wants to easily filter recipes, which she wants to see and recipes, she doesn’t want to see. While Tasty doesn’t offer a filter function, CookPad has a pretty nice filter function to filter out ingredients she wants and ingredients she doesn’t want. | Interface Design
/
Minor Problem
 | Anabella wishes she could just report the user/ recipe instead of reporting and blocking simultaneously, she would like to be able to follow up on the corrective action from CookPad but the design doesn‘t offer her the flexibility. (Flexibility) |
| Familiar Layout | Annabella doesn’t want to learn how to navigate in a new app. She wants to use the app right away. Both, CookPad and Tasty offers some familiar things in the app, which makes the use much more simpler. | Functional Specifications
/
Serious Problem | Annabella wishes she could replace that ingredient for something else instead of having to look for a new recipe. |

## Implementation of Ideas in The App

### Empathy in MealBestie

- In the Discover feature, Annabella finds recipes tailored to her preferences. With each interaction she has with the app, MealBestie learns more about her tastes. Additionally, a tag above each suggestion explains why the app has recommended it to her.

![sw03_6.png](sw03_6.png)

- Notifications: Annabella receives notifications tailored to her preferences. Since she only wants notifications from chat interactions within the app, she can adjust this in the settings.

### Familiarity and Intuition in MealBestie

- Filter Recipes: Annabella can easily filter the recipes by just typing in the ingredients she wants and the ones she doesn't want in the filter pop up. If she makes a typo, Mealbestie is still able to filter the recipes. For example, if she types "eG" instead of egg, the app will still get it. There are also two quick filter toggles for trending recipes and seasonal recipes.

![image.png](sw03_1.png)

- Familiar Layout: Annabella is already familiar with the navigation bar and icons from other apps, making it easy for her to quickly find her way around MealBestie. From day one, she’ll be able to navigate smoothly, using the app frequently as everything feels intuitive and user-friendly.

![image.png](oe_4.png)