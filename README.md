# ServiceNow Course Subscription Customization


This project contains the custom tables and configurations created in ServiceNow for managing course subscriptions. The application allows users to subscribe to courses, view their subscriptions, and manage their course data efficiently.

## Included Tables
- **Courses Table (`x_snc_course_subsc_courses`)**: 
  - Stores information about courses, including title, description, and duration.
  
- **Subscriptions Table (`x_snc_course_subsc_subscriptions_table`)**: 
  - Contains records of user subscriptions to courses, including user ID and course ID.

- **Users Table (`x_snc_course_subsc_users`)**: 
  - Holds user information that can be referenced when subscribing to courses.

## Installation Instructions
1. Log in to your ServiceNow instance.
2. Navigate to the System Import Sets > Load Data.
3. Choose the XML files you exported and click **Import**.
4. After importing, navigate to the respective tables to verify the data.

## Usage
- Users can subscribe to courses through the **Subscriptions Table**.
- Administrators can manage courses and view user subscriptions.