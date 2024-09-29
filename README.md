Movie Recommendation System


This project involves building a movie recommendation system using association rule mining on the MovieLens dataset. The objective is to develop an effective recommendation system that suggests movies based on the association between rated movies. The following steps document the progress made in the project.

Project Overview
The Movie Recommendation System is built using:

Dataset: MovieLens
Task: Data preprocessing and implementation of association rule mining for movie recommendations.
Technologies: Python, Jupyter Notebook, Git, GitHub
1. Setup the Git Repository
Repository Link: Movie-Recommendation-System
A new Git repository was created on GitHub to manage the project.
Git was initialized and the remote origin was set to the GitHub repository.
Commands:
bash
Copy code
git init
git remote add origin https://github.com/shuklaganesh/Movie-Recommendation-System.git
Achievement:
Successfully linked the local repository to GitHub for version control.
2. Data Preprocessing
We began by loading and preprocessing the MovieLens dataset.
Filtered users who rated more than 10 movies and retained movies with ratings above 2.
Split the dataset into training and test sets.
Key Steps:
Loading Data: Loaded the dataset using pandas from the CSV files (ratings.csv, movies.csv).
Filtering Data: Filtered users and movies based on specific conditions.
Splitting Data: Split the dataset into 80% training and 20% testing.
Achievement:
Completed data preprocessing, cleaning the dataset for further analysis and recommendation modeling.
3. Git Workflow for Preprocessing Commit
After preprocessing the data, the Jupyter notebook was committed and pushed to the GitHub repository.
Git commands were used to track, commit, and push changes.
Commands:
bash
Copy code
git add "Assignment 3_64_Mid-Submission.ipynb"
git commit -m "Completed data preprocessing for movie recommendation system"
git push -u origin main
Achievement:
Successfully committed and pushed the preprocessed data to GitHub.
4. Handling Common Issues
Line Ending Warning: While committing, we encountered the warning about "LF will be replaced by CRLF". This is related to line-ending differences between Unix/Linux and Windows. It's harmless and was handled by Git automatically.
Untracked Files: Git showed some untracked files, which were resolved by manually adding the required notebook file to the staging area.
Commands:
bash
Copy code
git add "Assignment 3_64_Mid-Submission.ipynb"
git status
git commit -m "Added preprocessing step for movie recommendation system"
git push -u origin main
Achievement:
Successfully resolved common Git issues and ensured the notebook was committed and pushed.
5. Progress Overview
We have successfully completed the following steps:
Repository Setup: Initialized the Git repository and linked it to GitHub.
Data Preprocessing: Loaded, cleaned, and split the dataset for further analysis.
Version Control: Successfully committed and pushed the preprocessing steps to GitHub.
Next Steps:
Implement association rule mining algorithms (such as Apriori or FP-Growth) on the preprocessed data to extract movie recommendations.
Evaluate the system using precision and recall to ensure accurate movie recommendations.
Continue pushing updates to GitHub as the project progresses.
Repository Structure
bash
Copy code
├── Assignment 3_64_Mid-Submission.ipynb  # Jupyter notebook containing preprocessing steps
├── README.md                             # This README document
How to Run the Project:
Clone the repository:
bash
Copy code
git clone https://github.com/shuklaganesh/Movie-Recommendation-System.git
Install dependencies: Ensure you have Python installed along with pandas and numpy.
Run the Jupyter notebook to replicate the preprocessing steps.
Author
Ganesh Shukla
Maria Deepika Alexander
