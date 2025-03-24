# WiDS Datathon 2025 - Team 13 Submission

This is a submission of our contribution to the WiDS Datathon on Kaggle as part of the Break Through Tech AI program.

## Contributors:

Anastasiia Kiseleva \
Cami Zheng \
Jasmine Wongphatarakul 

# Project Overview

### Mission

The WiDS 2025 Datathon focuses on women’s brain health, challenging participants to develop models that predict a patient's ADHD diagnosis. The competition aims to identify key brain regions linked to these conditions, advancing personalized medicine and therapeutic interventions. 

### Relation to Break Through Tech AI

Break Through Tech AI offers a comprehensive year-long program to teach students the fundamentals of machine learning and AI. Part of the program is participation in AI Studio, which lets students put their skills to use while tackling real-world challenges. By participating in this datathon, students gain relevant industry experience while learning more about the topic of women's health, bringing more awareness to gender gaps in research.

### Real-world Impact

This model has a lot of potential that can be leveraged to advance women's brain health research and treatment:

- Early Diagnosis: Enables timely interventions.

- Personalized Treatments: Supports gender-specific therapeutic strategies.

- Advancing Research: Improves understanding of brain health disparities.

# Data Exploration

### Dataset

Our team used the provided Kaggle dataset, which includes brain imaging measurements, demographic details, and neuropsychological assessments. As this dataset has been presented in a form of several separate Excel tables, it needed to be converted to Pandas DataFrame format for further exploration and feature scaling.

### Data Preprocessing

After displaying the test data, we have found that all datasets shared a ```participant_id``` column, confirming that all of the data can be combined into one dataset as each of the columns' values relate to a certain participant in all of the data files. 

<img width="895" alt="Screenshot" src="https://github.com/user-attachments/assets/e36faf34-ada7-436e-a7cb-8ea430cae7c3" />

After merging the dataset, we are able to get info on it:

<img width="874" alt="Screenshot" src="https://github.com/user-attachments/assets/6c102a94-8af0-4faa-ab69-269ff6155c6c" />

As we can see, there is a total of 1213 entries, meaning that there was a total of 1213 participants. Each participant potentially has up to 19928 (excluding ```ADHD_Outcome``` and ```participant_id```) features that can be leveraged to predict their ADHD diagnosis.

### Data Visualization

Let's build some graphs to visualise the data we will be working with:

<img width="564" alt="ADHD Sex/Outcome Distribusion Graph" src="https://github.com/user-attachments/assets/01f230cb-6958-4cdc-8b49-169f31f22f22" />




