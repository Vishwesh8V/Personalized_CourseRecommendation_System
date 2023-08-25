# Personalized_CourseRecommendation_System
A personalized course recommendation system which takes into consideration a student's grade history to recommend faculty and courses.
Personalized Course Recommendation System
Project Logo

Welcome to the Personalized Course Recommendation System repository! This project aims to revolutionize the way course recommendations are made for students. Instead of relying solely on past academic performance, we harness the power of machine learning and student feedback to provide personalized and insightful course recommendations.

Table of Contents
Project Description
Files
Getting Started
Usage
Contributors
License
Project Description
The existing course recommendation systems primarily consider academic records such as grades and CGPAs. However, we believe that a comprehensive course recommendation should also consider other factors. Our project leverages machine learning techniques to analyze student feedback about various aspects of courses and teachers, including teaching skills, friendliness, and course difficulty. This feedback, gathered from students who have already completed the course, is subjected to semantic analysis to extract meaningful insights.

The key features of our system include:

Semantic Analysis: We employ advanced natural language processing techniques to extract valuable information from student feedback.
Recomendation system: Our system provides real-time course recommendations based on both academic performance and the analyzed feedback.
Improved Student Experience: By offering a wider array of choices and more informed recommendations, we aim to enhance the overall academic journey of students.
Files
This repository contains the following files:

Indian_Names.csv: A few names to use in final dataset.
courses.csv: Courses names and Teacher rating, Teacher Friendliness, Course Difficulty, Teaching skills, credits.
courses_list.csv: List of Courses with division for each component.
ds.ipynb: code file for dataset.
feedback.ipynb: code file of feedback.
finalDataset0.4.csv: bag of words used to classify sentiment of a sentance.
rs.ipynb: recommendation system main code file.
student_preferences.csv: student preferences.
studentfeedback.csv: past student feedback.
students.csv: student grades.

Getting Started
To get started with the project, follow these steps:

Clone this repository to your local machine.
Open the provided Jupyter Notebook files (ds.ipynb, feedback.ipynb, rs.ipynb) using Jupyter Notebook or Jupyter Lab.
Explore the notebooks to understand the data preprocessing, analysis, and recommendation generation processes.
Usage
Here's how you can use our system:

Data Preparation: Ensure you have the required datasets, including courses.csv, student_preferences.csv, and studentfeedback.csv.
Analysis: Run the notebooks (ds.ipynb, feedback.ipynb, rs.ipynb) to perform data analysis, feedback processing, and recommendation generation.
Real-time Recommendations: Utilize the generated recommendation model to provide personalized course suggestions to students based on their academic performance and feedback.
Feel free to customize and integrate our system into your educational institution's infrastructure.
