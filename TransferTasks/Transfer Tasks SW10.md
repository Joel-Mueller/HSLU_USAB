# Transfer Tasks

- [🏠 Home](../index.md)
- [💪 SW10 - Consistency](<../SW10 - Consistency.md>) 

## Task 1
Go through all your screens and Test for external consistency - how did others do it?
Test for internal consistency on the levels content function and visuals.

1. Content: Are you using all texts in a consistent manner?
2. Function: Are all interactions, input-patterns and navigation consistent?
3. Visuals: Are all visual elements as fonts, colors, hierarchies, grouped elements consistent?
List your findings in a table


## External Consistency
**External Consistency Analysis**  
We compared our app with other cooking apps (like [example cooking apps - , Tasty, or CookPad]). Here’s what we observed:  

| Aspect           | How Others Do It                                      | Our Implementation                                |
|------------------|------------------------------------------------------|-------------------------------------------------|
| **Ingredient Substitution** | Ingredient replacement suggestions are common and simplified. | We provide “...” options for users to exclude or replace ingredients. Efficient but could use more streamlined visuals. |
| **Feedback Submission**     | Direct input box with instant confirmation is standard. | Implemented with a feedback text box and confirmation popup. Works well. |
| **Preferences**             | Centralized in a profile tab, allowing quick customization. | Achieved with "User Preferences" under Profile. Consistent and flexible. |

---

## Internal Consistency
**Internal Consistency Analysis**  
We tested the app for consistency in content, functionality, and visuals across all screens.

### 1. Content
| Screen/Section       | Findings                                                                               | Status       |
|-----------------------|---------------------------------------------------------------------------------------|--------------|
| **User Preferences**  | Text is clear and descriptive. Options like "Diet," "Language," and "Measurement" are consistent. | ✅ Consistent |
| **Ingredient List**   | Some placeholder text is used in descriptions. Needs standardization.                 | ⚠ Review Needed |
| **Navigation Buttons**| Button labels like "Go Back" and "Cook it!" are used consistently.                    | ✅ Consistent |

### 2. Function
| Screen/Section          | Findings                                                                 | Status       |
|--------------------------|-------------------------------------------------------------------------|--------------|
| **Navigation**           | "Profile > Preferences > Feedback" flows logically and consistently.    | ✅ Consistent |
| **Ingredient Substitution** | "..." menus allow replacement/exclusion; interaction is uniform.       | ✅ Consistent |
| **Feedback Submission**  | Submission process (input → confirmation popup) is consistent and intuitive. | ✅ Consistent |
| **Back Navigation**      | "Go Back" buttons appear consistently across all screens.               | ✅ Consistent |

### 3. Visuals
| Screen/Section        | Findings                                                                 | Status       |
|------------------------|-------------------------------------------------------------------------|--------------|
| **Fonts**             | Font type and size are consistent across all screens.                    | ✅ Consistent |
| **Colors**            | Primary and secondary colors are applied uniformly.                      | ✅ Consistent |
| **Icons & Buttons**   | Buttons/icons are consistent, but alignment could be improved slightly.  | ⚠ Review Alignment |
| **Grouped Elements**  | Grouping of user preferences, ingredients, and feedback is visually clear. | ✅ Consistent |
| **Feedback Pop-up**   | The popup confirmation message uses the correct hierarchy but could be styled better. | ⚠ Visual Improvement |

---


## Task 2
Study the consistency framework in the slides and step through your product and try to think through all the elements of the framework. Below you see the consistency-frameworl ordered as you would do it during a project. Now add your own considerations (right column) that relate to your project. Now adjust your project according to your considerations or comment on what you would do if you can't implement it directly.


| | **Consistency Type** | **Thoughts** |
|-|-|-|
| 1. |	Induced Inconsistency (External consistency) |	It is important to be visually inconsistent, so the user knows when something acts different than another thing. “Make objects that act differently look different”. We need to consider which external consistencies are present and which need to be taken into account. |
| 2. |	Consistency with User-Expectations	| Knowledge about the users and their experiences/expectations is crucial. We must derive the UI from the context (cooking, finance, games) and the expectations of the user. |
| 3. |	Continuity | We need to strive for continuity over time. If an app is released as a new version of the last, it should follow some consistencies from the older one that can guide the user while still having a level of innovation in comparison. |
| 4. |	Induced Inconsistency (Internal consistency) |	What can we use to draw the attention of the users and communicate with them how the app works (colors, icons, etc)? |
| 5. |	Functional Consistency Navigation (Internal consistency) | Where do we place what and how do we do things in our app? We can ensure consistency in how we place form fields and buttons, how our homepage looks and so on. |
| 6. | Visual consistency, layout, muster Schrift, Icons (Internal consistency) |	The symbols, icons, and images we used should be consistent across the app. This includes things like the border color and weight of the images on our site, the color scheme we use, the icons we use on each page. |
| 7. |	Content Text & Tonality (Internal consistency) |	Depending on the message you want to share or how you want your app to look to users you need to set the tone and stick to it (comedic, smart, witty, friendly, etc.) |