Dating App Simulation

Overview:
This project implements a recommendation system for a dating app using Python. The system suggests profiles to users based on compatibility scores calculated from shared attributes such as age, interests, and location. Users can interact with suggested profiles by liking or disliking them, which dynamically updates the recommendation scores.

Features:
- Scoring Algorithm: Calculates compatibility scores between profiles based on attribute matches.
- Recommendation Process: Selects and presents profiles to users in descending order of compatibility scores.
- User Interaction: Allows users to provide feedback (like or dislike) on suggested profiles, updating scores and marking profiles as interacted.

Setup:

1. Install Dependencies:
   - Ensure Python 3.x and pip are installed.
   - Install required libraries:
     pip install pandas

2. Data Setup:
   - Place your profile data in a CSV file named person_data.csv.
   - Ensure the CSV file includes columns for attributes like Name, Age, Interests, etc.

3. Usage:
   - Run the interaction script:
     python interact.py
   - Follow on-screen instructions to interact with the recommendation system.

Files and Structure:
- interact.py: Main script for user interaction and system operation.
- person_data.csv: CSV file containing user profile data.
- README.txt: This file, providing project overview, setup instructions, and usage details.
- updated_scores.csv: Output file containing updated scores after each interaction.

Implementation Details:
- Data Handling: Uses Pandas to load and manipulate profile data from person_data.csv.
- Scoring Method: Implements a simplified scoring algorithm based on attribute comparisons.
- Future Improvements: Consider integrating advanced algorithms (e.g., matrix factorization) for enhanced recommendation accuracy.
