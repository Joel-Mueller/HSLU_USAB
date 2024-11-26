# Old empathy

## Situation

Annabella wants to cook something, she goes into her kitchen, opens the app she had wanted to try, but if the app isn’t well designed, she could run in some hurdles. These could be:

- She finds it difficult to navigate, she doesn’t at first find the page where the recipes are listed
- The recipe is displayed as a big block of text, which she gets lost in the process of cooking
- She can’t find the recipe that she saw yesterday and wanted to try today
- She doesn’t have broccoli in her fridge, because of that, she feels that the can’t cook the meal
- She doesn’t know what recipes are well liked by the community
- She finds a few recipes with strawberries, but it’s currently winter
- She is lactose intolerant and sees a lot or recipes which have milk in it
- After the cooking thinks a recipe isn’t good. She wants to let the other people know it
- The registration is long and tedious before she can cook something

## Empathy analysis

Based on these 10 Questions, we will analyse first two apps that are similar to our app in the section empathy. We try to unserstand how Airbnb and Linked in solves this empathy hurdles. Afterwards, we show how we implement these features.

### 1. **What makes your product intuitive for the target group?**

- **LinkedIn**: Has an intuitive layout with defined sections like "Jobs," "My Network," and "Messages" to make it easy to navigate. With this design, the target group “professionals” can find easy what they need

![oe_2.png](oe_2.png)

- **Airbnb**: Simple navigation for finding accommodations by destination, check-in/out dates, and guests. The target group can filter after their preferences very easy and quickly

![image.png](oe_1.png)

- Our implementation
    - **Simple navigation**: In our tab bar, the user can choose between discovering new recipes, the recipes marked as favourites, upcoming events and messaging services.
    
    ![image.png](oe_3.png)
    
    - **Step-by-step instructions**: Each recipe is as easy as possible to cook
    
    ![image.png](oe_5.png)
    
    - **Search and filter functionality**: Users can search for recipes by vegetables and fruits that are in season
    
    ![image.png](oe_6.png)
    

### 2. **Which familiar elements do you use?**

- **LinkedIn**: Uses familiar social media elements like newsfeeds, likes, and shares, which users recognise from platforms like Instagram. It also offers a messaging system similar to traditional email or direct messaging.

![image.png](oe_7.png)

- **Airbnb**: Familiar elements like user reviews and ratings for properties, as well as a heart icon to save favorite listings or the share button.

![image.png](oe_9.png)

- Our implementation
    - **Bookmarking/favourites**: Users can save their favourite recipes for easy and fast access like a video from instagram
    
    ![image.png](oe_8.png)
    
    - **Ratings**: People can rate a recipe with the well known 5-star system. They already know this from google, amazon, blogs and a lot of other sites. The average rating can then be viewd on the homepage
        
        ![image.png](oe_10.png)
        
        ![image.png](oe_11.png)
        

### 3. **Errors can occur**

- **LinkedIn**: You get advertisements served, you maybe don’t want to see or being associated with. With linked in, you can hide, report the add or asking why you see the advertisement.

![image.png](oe_15.png)

- **Airbnb**: Errors can occur when a guest books accommodation that isn’t accurately described, leading to dissatisfaction. A user can report this issue.
- Our Implementation
    - **Ingredient substitutions**: If a user follows a recipe and substitutes an ingredient that doesn’t work well, the result could be unsatisfactory. We want to offer a feature where the user can substitute a product properly.
    
    ![image.png](oe_14.png)
    

### 4. **Special trust, security, data protection is required**

- **LinkedIn**: Users trust LinkedIn with their professional history and sensitive career-related information. The user also sends direct messages to other users within the app
- **Airbnb**: People give a lot of user data to airbnb like what they like and what their type of vacation is. When they eventually book something, the user gives their credit card and personal information to Airbnb.
- Our implementation
    - **Account creation and storage**: Protect personal details like dietary preferences, saved recipes, and account info with encryption.
    - **Permissions**: Request only necessary permissions, such as location for finding nearby events.

### 5. **What could prevent use?**

- **LinkedIn**: When the user has no success finding what he wants to find
- **Airbnb**: If there are too many steps before booking an apartment like sign up, giving the information about the guest and so on.
- In our implementation
    - **Complex registration**: We want the registration prozess as easy as possible. The user should be able to use the app almost right away. Therefore, we would implement a sing up with  Google, Apple or Amazon feature.
    - **Overwhelming interface**: If there are too many features, the user gets confused or overwhelmed. In our app, the user has not to many features. But for the things he wants to use the app, it is as easy as possible.
    
    ![image.png](oe_13.png)
    
    - **Device compatibility**: If the app isn’t optimised for various devices. Our app should be on the Google Play store and on the App Store. Furthermore, the app should be also on the web, so when the user has no iPhone or Android phone, he will be able to use the app through the browser.

### 6. **In which step does the user feel like? Are there situations that could be unfavourable?** Can something be annoying depending on the situation?

- **LinkedIn**: When the user gets annoying emails or push notifications, where he doesn’t show interest.

![image.png](oe_12.png)

- **Airbnb**: A guest could feel overwhelmed when trying to book accommodation in a popular destination with too many options or too few relevant results.
- Our solution
    - **Finding the right recipes**: If a user has some allergies, or just has some special preferences, he should be able to find the right recipes, which fits for him.
    - **Annoying ads or notifications**: The app only pushes relevant notifications. If the user doesn’t react to these notification, the user won’t get them anymore. The app should also be free from ads.

### 8. **Is the user always in control?**

- **LinkedIn**: Users control who they connect with, who can view their profile, and what notifications they receive. They can also control their visibility to recruiters.
- **Airbnb**: Guests can adjust booking preferences (price, amenities, cancellation policies), and hosts can set their rules (minimum stays, check-in times). Both parties have the option to cancel under certain conditions.

![image.png](oe_1.png)

- Our implementation
    - **Ingredient toggles**: Users can switch out ingredients they don’t like, and the app provides suggestions for alternatives.
    - **Step-by-step guidance**: Users can progress through recipes at their own pace without feeling rushed.

### 9. **Can a change in personal situation lead to a new perception of features?**

- **LinkedIn**: If a user transitions from job-seeking to a full-time position, they may find the job recommendations and recruiter messages less relevant. The user might prioritise other features like learning or networking.
- **Airbnb**: A user who initially looks for budget accommodations may later seek more luxurious stays if their financial situation improves. Recommendations have to adjusted.
- Our implementation
    - **Dietary changes**: If a user becomes vegan or needs to avoid allergens, they might appreciate the app’s ability to filter out unsuitable recipes. The user should also be able to report a notification or recommendation if he sees that it doesn’t fit for them.

### 10. **Measures to ensure continued app use**

- **LinkedIn**: Linked in has articles based on user’s interest to keep them engaged even when they're not actively job-hunting.
- **Airbnb**: Introduces new features like "Experiences" (activities hosted by locals) or seasonal promotions to keep users coming back, even when they aren't booking accommodations.
- Our implementation
    - **Regular new content**: Constantly add new recipes or seasonal features to keep the app fresh.
    - **Personalised recommendations**: Use machine learning to suggest recipes based on past user behaviour.
    - **Seasonal notifications**: Notify users of new recipes, based on the vegetables and fruits which are season.

## Summary

| **Question** | **LinkedIn** | **Airbnb** | **Our Implementation** |
| --- | --- | --- | --- |
| **1. What makes your product intuitive for the target group?** | Defined sections like "Jobs," "My Network," etc. | Simple navigation for finding accommodations | Simple navigation, step-by-step instructions, search and filter by season |
| **2. Which familiar elements do you use?** | Newsfeeds, likes, shares, messaging | User reviews, ratings, heart icon for favorites | Bookmarking, upvote/downvote, visual recipe cards |
| **3. Errors can occur** | Ads may be unwanted but can be hidden or reported | Booking issues due to inaccurate descriptions | Ingredient substitutions feature for better alternatives |
| **4. Special trust, security, data protection is required** | Stores sensitive career information | Personal info, credit card for bookings | Encryption for personal details, minimal permissions |
| **5. What could prevent use?** | Inability to find desired content | Too many steps before booking | Easy registration (Google, Apple, Amazon), minimal features, compatibility with all devices |
| **6. Situations where the user might feel overwhelmed** | Unwanted emails or push notifications | Overwhelming accommodation options | Filtering for allergies/preferences, no annoying ads, relevant notifications only |
| **8. Is the user always in control?** | Control over profile, connections, notifications | Adjust booking preferences, cancel conditions | Ingredient toggles, step-by-step recipe guidance |
| **9. Can a change in personal situation lead to a new perception of features?** | Shift from job-seeking to networking | Budget to luxury accommodations | Filters for dietary changes (vegan, allergens) |
| **10. Measures to ensure continued app use** | Articles for engagement, learning opportunities | New features like "Experiences" and promotions | New recipes, personalised suggestions, seasonal notifications |