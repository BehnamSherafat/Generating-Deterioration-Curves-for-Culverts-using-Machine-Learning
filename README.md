# Generating-Deterioration-Curves-for-Culverts-using-Machin-Learning
In this project, I generated deterioration curves for Utah culverts using machine learning techniques such as random forest regression and support vector regression.

## Keywords
1. Deterioration Curves
2. Utah Culvert
3. Data Science
4. Machine learning models
5. Support Vector Regression (SVR)
6. Random forest regression
7. Feature engineering
8. Feature importance
9. RandomizedSearchCV
10. Features used (most of the data is collected from available websites and datasets):
  Soil conditions (Drainage Class, Moisture, pH, Electrical Conductivity, Surface Texture,	Flooding Frequency)
  road conditions (Route ID,	Route Number,	Reference Post,	Accumulate Mileage,	Average AADT,	Latitude,	Longitude,	Highway,	Roadway cover (inch),	Road Surface Type	Road Region,	Shoulder Surface Type)
  weather conditions (temperature and precipitation)
  culvert pipe condition (pipe material, pipe shape, pipe coating type, barrel count, barrel height, barrel width, barrel depth, barrel length)

## Introduction
Historical data from current and previous field inspections conducted by UDOT personnel and consultants are utilized to generate culverts’ deterioration curves, inspection frequency schedules, and life service reports. I Identify the culvert importance (i.e., inspection priority), generated culvert inspection frequency (i.e., culvert inspection schedule), conducted life cycle cost analysis, risk analysis, and predicted the culvert service life.

## Programming Language Used
Python

## Guide to folders and files
Codes are explained as follows:
1. PreProcessUtahCulverts.ipynb
2. UtahCulvertsInspection.ipynb
      
## Collected Datasets:
1. Colorado
2. Utah
3. Vermont

## Methodology
![image](https://user-images.githubusercontent.com/73087167/185808969-a31c9898-5450-4d1c-bbf9-0b0ee9fe018a.png)

## Data Collection
![image](https://user-images.githubusercontent.com/73087167/185808998-eb16c115-a725-463a-94c8-9b644246727f.png)

## Generated Deterioration Curves
![image](https://user-images.githubusercontent.com/73087167/185809001-6335205f-49a6-4ca5-b68c-4ecbf5fa670f.png)

## Identified Risk Cost and Risk Category
![image](https://user-images.githubusercontent.com/73087167/185809028-f6a6dd9a-2fc4-443c-85f5-20aa08d6508e.png)

## Identified Risk Matrix and Risk Levels
![image](https://user-images.githubusercontent.com/73087167/185809052-fc57ca46-e501-4e27-9b20-14fac4d42217.png)

## Identified Inspection Frequencies
![image](https://user-images.githubusercontent.com/73087167/185809067-0c15386f-e8e9-4fc6-a57f-a11c14c974a6.png)




