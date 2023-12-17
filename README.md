
### Objective
Developed an automated system to screen and evaluate resumes for job applicant suitability using natural language processing and machine learning techniques.

### Tools & Technologies
Python, Jupyter Notebooks, Scikit-learn, Pandas, TfidfVectorizer, Pickle

### Steps
- Preprocessed a dataset of resumes (UpdatedResumeDataSet.csv) using Pandas for data cleaning and manipulation.
- Employed TfidfVectorizer to convert the resume text into a matrix of TF-IDF features, facilitating the identification of relevant skills and experience.
- Trained a machine learning classifier  to categorize resumes into different job profiles or predict the suitability of candidates.
- Serialized the trained TfidfVectorizer and classifier model using Pickle for deployment, enabling quick resume screening on new datasets without retraining.


