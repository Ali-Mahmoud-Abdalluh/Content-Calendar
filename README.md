# 30-Day Content Planner

## Description

The 30-Day Content Planner is a web application designed to help businesses and individuals generate content ideas and schedule them for social media and other platforms. It provides a structured approach to content creation, offering features like:

* **Content Idea Generation:** Generates 30 days' worth of content ideas based on the user's business type or niche.
* **Scheduling Recommendations:** Provides platform-specific scheduling recommendations.
* **Hashtag Suggestions:** Generates relevant hashtags to increase content visibility.
* **CSV Export:** Allows users to export their content plan to a CSV file.
* **Save for Later:** Stores the content plan in local storage for future access.

## Features

* **Business Type Input:** Users can input their business type or niche to tailor content ideas.
* **Content Ideas:** The application generates 30 unique content ideas, including the content type (e.g., blog post, video, social media post) and a suggested title.
* **Scheduling Recommendations:** The application provides recommendations for which platforms are best suited for each content type, and suggests a weekly posting schedule.
* **Hashtag Suggestions:** The application generates a list of relevant hashtags that users can copy and use in their social media posts.
* **CSV Export:** Users can export the generated content ideas to a CSV file for easy sharing or integration with other tools.
* **Save for Later:** The application automatically saves the generated content plan in the user's browser's local storage, and notifies the user upon return if a plan is available.

## How to Use

1.  **Enter Business Type:** Enter your business type or niche in the input field.
2.  **Generate Content Ideas:** Click the "Generate Content Ideas" button.
3.  **View Results:** The application will display:
    * 30 content ideas
    * Scheduling recommendations
    * Hashtag suggestions
4.  **Export to CSV:** Click the "Export to CSV" button to download the content plan.

## Technologies Used

* HTML
* CSS (Tailwind CSS)
* JavaScript

## Code Structure

* `index.html`: Contains the HTML structure of the application, including the form, results display, and export button.
* `style.css`: Contains the CSS styling for the application.
* `script.js`: Contains the JavaScript logic for generating content ideas, scheduling recommendations, hashtag suggestions, and handling user interactions.

## Key Functions

* `generateContentIdeas(businessType)`: Generates an array of content ideas for 30 days.
* `generateTitle(businessType, type)`: Generates a content title based on the business type and content type.
* `displayContentIdeas(ideas)`: Displays the generated content ideas in the HTML.
* `displaySchedulingRecommendations(businessType)`: Displays platform-specific scheduling recommendations.
* `getPlatformRecommendations(businessType)`: Gets platform recommendations based on Business Type.
* `displayHashtagSuggestions(businessType)`: Displays hashtag suggestions.
* `generateHashtags(businessType)`: Generates relevant hashtags based on the business type.

## Enhancements

* The application includes a "Save for Later" feature that stores the generated content plan in local storage and notifies users of their saved plan on return.
* The application provides platform-specific recommendations
* The application generates relevant hashtags.

## Future Improvements

* Add more sophisticated content idea generation algorithms.
* Allow users to customize the number of content ideas.
* Integrate with social media platforms for direct scheduling.
* Add a feature to track content performance.
