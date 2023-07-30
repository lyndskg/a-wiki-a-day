# a-wiki-a-day

a-wiki-a-day is an innovative web and iOS app that allows users to subscribe to a daily email, text, or push notification containing an interesting Wikipedia page or link. The app utilizes a random article generator using the Wikipedia API, but its uniqueness lies in using Machine Learning (ML) to filter and fine-tune articles, tailoring them to the individual interests of each user. By considering criteria such as category, popularity, length, keywords, geographic or historical relevance, and user feedback, a-wiki-a-day delivers the most personalized and captivating article recommendations to its users.

## Key Features:
1. Random Article Generator: a-wiki-a-day's core functionality is the random article generator, which fetches a Wikipedia page or link using the Wikipedia API.
2. Machine Learning Filters: The ML model is designed to filter and fine-tune articles based on multiple factors, such as category preferences, article popularity, length, and relevance to user-defined keywords.
3. User Preferences: The app allows users to set their interests, select preferred article categories, and specify keywords relevant to their hobbies, passions, or academic fields.
4. Geographic and Historical Relevance: Users can also specify preferences related to specific regions or historical periods, enabling a-wiki-a-day to offer more contextually relevant articles.
5. Feedback Mechanism: a-wiki-a-day includes a feedback mechanism where users can rate articles as "interesting" or "not interesting." This feedback helps improve the selection criteria for better recommendations over time.
6. Personalized Recommendations: The ML model learns from user feedback and preferences to provide personalized article recommendations, making each daily notification more engaging and exciting.
7. Multi-Platform Accessibility: a-wiki-a-day is accessible as a web app and an iOS app, providing convenience for users to access interesting Wikipedia content on their preferred devices.

## Best Coding Languages:
Python is an ideal choice for this project, as it offers robust ML libraries and tools for data processing. For the web app, you can use JavaScript for the frontend and Django or Flask for the backend. For the iOS app, Swift is the recommended language.

## Basic Workflow:
1. Wikipedia API Integration: Integrate the Wikipedia API to fetch random articles and related metadata.
2. User Profile Setup: Allow users to set their preferences, including category choices, keywords, and geographic or historical relevance.
3. ML Model Development: Design and train the ML model using user feedback and various filtering criteria to deliver personalized recommendations.
4. Daily Notifications: Implement a scheduler to send daily email, text, or push notifications containing the recommended Wikipedia articles to subscribers.
5. User Feedback Collection: Set up a feedback mechanism for users to rate articles and provide input on their level of interest.
6. Continuous Improvement: Use the collected feedback to refine the ML model and enhance the filtering algorithms for more accurate and enjoyable recommendations.


## Basic I/O Details:
1. Users input their preferences and subscribe to receive daily notifications through their preferred communication channel (email, text, or push notification).
2. The app sends the selected Wikipedia page/link as a daily notification, based on the ML-generated recommendations.
3. Users can rate articles or mark them as "interesting" or "not interesting" through the app's interface, which helps enhance future recommendations.


a-wiki-a-day aims to bring personalized and fascinating Wikipedia content to users, making it an engaging and educational platform for daily exploration.
