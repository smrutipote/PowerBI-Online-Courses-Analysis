
Online Course Analysis Dashboard

📌 Project Overview

This project is designed for an EdTech startup that aims to expand its offerings in recorded lectures. The startup has gathered data from various EdTech platforms and seeks data-driven insights to refine its strategy. The Power BI dashboard included in this repository provides a comprehensive analysis of course categories, viewer engagement, language preferences, instructor ratings, and subtitle impact on engagement.

📌 Data : https://www.kaggle.com/datasets/khaledatef1/online-courses

🎯 Key Insights & Analysis

1️⃣ Course Distribution by Category & Sub-category

![course type popularity](https://github.com/user-attachments/assets/1e562108-7047-4b3e-bbf6-0b1befdd8303)

Visual Representation: A bar chart displaying the number of courses per category and sub-category.

Insights: Helps determine which categories are dominant and where new courses can be introduced.

Use Case: Guides the startup in selecting the most suitable categories for launching new courses based on current distribution trends.

2️⃣ Average Number of Views per Category, Sub-category & Language

Visual Representation: A multi-level bar chart comparing the average views.

Insights: Provides insights into viewer engagement patterns to help prioritize course development.

Use Case: Helps identify high-demand categories, subcategories, and languages to maximize engagement.

3️⃣ Top Skills Taught by Category

Visual Representation: A word cloud representation of the most commonly taught skills within each category.

Insights: Helps align course offerings with industry trends and market demand.

Use Case: Enables the startup to tailor course content according to skills currently in high demand.

4️⃣ Distribution of Languages Across Courses

Visual Representation: A pie chart representation of the proportion of courses in different languages.

Insights: Identifies the most widely used languages for course creation.

Use Case: Helps in strategic decision-making regarding language preferences for future courses.

5️⃣ Language Preferences for the Top 5 Categories

![preferred course language](https://github.com/user-attachments/assets/a83716fa-e1e1-4de1-b365-ae18294aa498)

Visual Representation: A stacked bar chart showing the top 5 categories based on user preferences and their language distribution.

Insights: Helps optimize course accessibility and ensure alignment with audience demand.

Use Case: Allows the startup to adjust course translations and subtitles accordingly.

6️⃣ Impact of Subtitles on Course Views

Visual Representation: A scatter plot showing the relationship between subtitle availability and course views.

Insights: Determines if adding subtitles enhances engagement and accessibility.

Use Case: Guides the decision on whether subtitles should be prioritized for increasing engagement.

7️⃣ Top 3 Instructors per Category & Sub-category Based on Ratings

Visual Representation: A static table listing the highest-rated instructors for each category and sub-category.

Insights: Helps the client identify top-performing educators who can be approached for collaboration.

Use Case: Enables the startup to form partnerships with top-rated educators to improve course quality.

🛠 Technical Details

Tool Used: Power BI

File Format: .pbix

Data Cleaning & Transformation: Power Query

📌 Measures & DAX Calculations:

Total Courses = COUNT(CourseID)

Average Views = AVERAGE(Views)

Top 5 Categories by User Preferences = [Calculated based on user engagement]

Instructor Ratings = AVERAGE(Rating)

Subtitle Impact = Correlation between subtitle availability and views

Course Count by Category & Sub-category = COUNTROWS(CourseTable)

Average Views by Language = AVERAGE(Views) GROUPED BY Language

Instructor Performance Score = COMBINATION OF Ratings, Reviews & Views

🚀 How to Use the Dashboard

Download the online_course_analysis.pbix file from this repository.

Open the file using Power BI Desktop.

Explore various visuals and filters to derive insights.

Use slicers and category-based filters to analyze specific trends and comparisons.
