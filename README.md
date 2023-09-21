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

### Some code snippets-


- The code below scrapes data of chiropractors from Practo in cities like Bangalore, Delhi, and Mumbai, by automating web browsing with Selenium and Chrome WebDriver.
- Then it stores the extracted information in an empty DataFrame.
![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/95f82406-0df7-4885-ae19-22301765c0aa)


- This code snippet collects detailed information about chiropractors from Practo by parsing the web page's HTML using BeautifulSoup. 
- It iterates through the listings, extracts data such as the doctor's name, degree, years of experience, location, DP score, NPV, and consultation fee, and then appends this information to the previously created DataFrame for each chiropractor found in the specified cities.
![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/bd1dbd99-e9dc-4ad5-8119-0b0a537b9660)
![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/08a8449a-2f7f-42b3-9610-8dae5087f6d4)

- The data scraped will get appended in the dataframe as shown below.

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/1373a028-512c-4188-871e-40033a592534)

- The above code snippet extracts data for just one specialization of doctor(Chiropractor), similarly we just replaced the url with respect to different specializations.

## CSV File

- The image below shows the csv file that was created by appending all the scrapped data into different dataframes.
- All csv files were concatenated into a single csv which is also uploaded in the folder in this repository.

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/b7bf92b4-f240-47f7-a596-2cae75d5427c)

## HTML File

- This HTML code snippet represents a basic webpage for "Doctor Fees Prediction."
- It includes jQuery and jQuery UI libraries, sets up some basic styling, and defines the structure of the webpage.
![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/c3efaacc-35a1-4af6-b259-c0b358c3fb90)

- This HTML code snippet represents a form for "Doctor Fees Prediction." It includes various input fields and a submit button within a <form> element.
![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/6bf67f52-8b2f-415e-8f35-f0090d73de91)


## Flask File

- This Python Flask code sets up a web app for predicting doctor fees using a pre-trained machine learning model.
- Users input data via a form, which is processed to provide a fee prediction displayed on the webpage.
- You can find the entire code in the file named app.py in this repository
![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/98f3df17-76ff-41c4-a5b3-f3377d12cf4f)


## Web Page
- This screenshot below provides a visual representation of the web page created for predicting doctor fees using a Flask-based web application.
![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/c8d2ed7d-be90-48bc-b210-eb7b74754fa6)



## **--Insights--**


- ###  Number of Doctors by each City

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/6ee38a22-cc5e-460b-9027-d406c93be503)
![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/7f9a3daf-4495-49b3-9b85-8d3fbf8bb228)


Highest number of doctors are from Bangalore(2169) whereas Mumbai has 1458 doctors listed in the website.

- ###  Number of Doctors in different specialities

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/0fd3de42-a3ff-4bcd-97ef-e4498a0fd0d8)


The majority of doctors specialize in Dentistry(1460), while the fewest doctors are Chiropractors (7).

- ###  KDE plot

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/d64190d2-1640-48f5-9c82-8f58e429b20e)


The plot above is showing that majority of doctors are in the range of experience between 13 to 15 years.

- ###  Count of top specializations among the doctors

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/2b7d7bcf-5f05-47f1-b1b9-d26b87988336)


BDS(Bachelor of Dental Surgery) is the most common degree among the doctors, which is clearly explainableas the highest no. of doctors are Dentists.

- ###  Speciality wise fees of doctors

![image](https://github.com/sarthak0613/doctors-fee-prediction/assets/135547703/82505fcf-13ee-4df3-a4c8-606ff567bd67)


Neurosurgeons and Ophthalmologists charge high consultation fees, while specialties like Dentistry, Dermatology, Gynecology/Obstetrics, Infertility Specialists, Physiotherapy, and Dietetics/Nutritionists offer almost free consultations.

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
