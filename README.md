 # Doctor's Fee Prediction Model


![1_s2sSUmiJGjitCLgjZA8H4w](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/0ebfff75-5931-42dd-9c9b-71995f3c7d2b)



## **--Introduction--**

Welcome to the repository for Doctor's Fee Prediction Machine Learning model! In this repository, I present an innovative solution aimed at predicting medical consultation fees based on various relevant factors. Whether you're a patient, healthcare professional, upcoming doctor or a data enthusiast, this project offers valuable insights into predicting the financial aspect of medical services.

## **--Problem Aimed to Solve--**

This project takes into consideration a number of factors such as Speciality of Doctor, Degree Type, Year of Experience, DP Score, City etc. for predicting the Doctor's fees which certainly helps patients and upcoming doctors to have an idea about it.

## **--Approach--**

![Web Scraping in](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/ed915bd9-3006-46a9-8214-51730014e600)

## **--Data Description--**

1. ML Model Files- These files includes the .ipynb Jupyter Notebook files wherein we have developed the Regression model for our project from the data by importing the .csv file that we got after web scraping of the practo.com website. It also contains a .pkl file which is the pickle file of our project.

2. CSV File- The final csv is included in this folder where we have uploaded the csv which we made after web scraping. The csv file contains a table which has columns such as Name, Speciality, Degree of doctor, Years of experience, Location, City, NPV, DP score and Consultation Fee. These are the factors as discussed earlier around which our project runs and predicts the fees.

3. Python Files- This folder contains all the .ipynb Jupyter Notebook files of the doctor's specialisation wise web scraping. Data of each specialisation is being scraped in each of the .ipynb files.

4. Web Page Files- We created a web page using HTML and deployed our ML model into it using flask. This folder contains the main HTML file, app.py file where we have imported flask library of python and deployed our ML model.

5. PPT- We have created an aesthetic presentation for the viewers to have a brief idea on the objective of this model, flow of our project, major insights, etc. PPT file is included in this folder.


## Machine learning model-
In this project, we use a linear regression model to predict doctor's fees. Linear regression is a simple yet effective technique for modeling relationships between a dependent variable (doctor's fee ) and one or more independent variables (features).

### Variables-
- speciality_of_doctor: Specialty of the doctor
- degree_type: Type of degree (e.g., MBBS, MD, BDS)
- year_of_experience: Total years of experience
- Location: Clinic location
- city: City of the clinic
- dp_score: Doctor-patient experience score
- npv_: Number of people's votes



## Web Scraping-

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/d96f2515-adff-48e3-84a5-e6be490fa116)


![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/af8dbac2-46a1-406b-9585-2cb28fd3c788)


## CSV File

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/b7bf92b4-f240-47f7-a596-2cae75d5427c)

## HTML File

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/9a650a0e-edd8-4607-9158-9ae8a67c9812)

## Flask File

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/a32cf47b-3a7a-4a84-96b3-1f7548ba7d13)

## Web Page

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/c8d2ed7d-be90-48bc-b210-eb7b74754fa6)



## **--Insights--**


- ###  Number of Doctors by each City

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/515385f5-54bc-43a7-9a9c-a9b05c95ba1b)

- ### Percentage Distribution of doctors in each city

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/1dfba316-5b20-4eec-b745-3007e49fbd1a)

- ###  Number of Doctors in different specialities

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/8253459f-fd16-444e-a70d-c2325d248772)

- ###  KDE plot showing that majority of doctors are in the range of experience between 13 to 15 years.

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/3110fa97-1046-40db-a33d-11d8b8a617b9)

- ###  Count of top degrees among the doctors

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/3bfa75e1-9d31-4927-834a-b2fee51d8b07)

- ###  Speciality wise fees of doctors

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/dfa4b1e1-096b-4211-a434-95ef3978eefc)

## **--Some key Insights--**

- Most of the doctors have 13 to 15 years of experience.

- Cities like Bangalore have a higher percentage of doctors, accounting for approximately 40.23%.

- The majority of doctors specialize in Dentistry (1460), while the fewest doctors specialize in Chiropractic (7).

- Bangalore has the highest number of doctors compared to Delhi and Mumbai.

- In each city, the number of dentists is higher than other specialties because their consultation fees are completely free.

- Neurosurgeons and Ophthalmologists charge high consultation fees, while specialties like Dentistry, Dermatology, Gynecology/Obstetrics, Infertility Specialists, Physiotherapy, and Dietetics/Nutritionists offer almost free consultations.

## **--Future scope--**

- This fee predictor can help upcoming doctors who are looking to set up their clinic to have an idea of how much other doctors are charging.
- Patients can have an idea of how much they are likely to be charged based on the factors that are mentioned in the model.
- A doctor looking to expand his/her clinic to other cities can also have an idea how much doctors are charging in that particulr city of an area of the city.

## **--Problems faced--**

- Faced problems while deploying the model onto the webpage, tackled it by referring to the free resources and tutorials available on YouTube.
- Having little knowledge about HTML and CSS, it was difficult to make a webpage, but took reference from YouTube and ChatGPT.
