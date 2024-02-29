# Campus-Placement-Predictor
# Overview
  Campus Placement Predictor is a machine learning project designed to predict the likelihood of a student getting placed during campus placements based on various academic and personal features. 
  The project aims to assist students in understanding their chances of securing a job offer during campus recruitment.

# Features
Input features include:
 - Secondary Education Percentage
 - Higher Secondary Education Percentage
 - Degree Percentage
 - Specialization
 - Work Experience
 - Internship Experience
 - Technical Skills
 - Communication Skills
 - Personality Traits

Target variable: Placement Status (Placed/Not Placed)

# Getting Started
# Prerequisites
Ensure you have the following dependencies installed:
 - Python (>=3.6)
 - NumPy
 - Pandas
 - Scikit-learn
 - Matplotlib
 - Seaborn

# Install dependencies using:

# bash
pip install numpy pandas scikit-learn matplotlib seaborn
# Usage
Clone the repository:
# Run the main script:
# bash
python campus_placement_predictor.py

# Follow the on-screen instructions to input academic and personal data.
# Machine Learning Model
  Algorithm: Random Forest Classifier
  Model training and testing performed on the Campus Placement dataset.
# Files and Directories
  campus_placement_predictor.py: Main script for user interaction and prediction.
  model_rf_campus_placement: Pre-trained machine learning model saved using joblib.
  data/: Directory containing the Campus Placement dataset.
# Results
The model achieved an accuracy of X% on the testing dataset.

License
This project is licensed under the MIT License - see the [LICENSE] file for details.
