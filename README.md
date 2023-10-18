# Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data.

The aim and objective of this analysis is to enable the management of the institution to make an informed decision on the fitness of the medical students and also plans for their sports outfits sizes(measurements) in view of their graduation sports festival coming up before the graduation ceremony.
---
### Parameters For Physical Fitness/Sports Wears Size (Male and Female) are as follows:
-  Average Age
-  Average Heart Rate
-  Average Blood Pressure
-  Bood Type
-  Students Who Smoke or Who Don't
-  Students who are Diabetic or Not
-  Average BMI
-  Average Cholesterol
-  Average Weight
-  Average Height 
---
#### Below is a snippet of the raw data of the Medical students 2020 class obtained from the school registrar, we can observe that some students data are missing in some cells.

![](https://github.com/vinemadukpe/Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data./blob/main/MDS00.png)
---

Before the above data can be use to obtain the required insights, I have to clean the raw data by following the below steps:
-  For Students ID, I used fill down series option to repair the column
-  For Height column, I used GoTo function to find the blank cells then replace them with the average height 119.83.
-  For BMI I used GoTo function and replace the blank cells with the average BMI 23.34
-  For Temperature, I used GoTo function to replace the blank cells with average temperature 98.60
-  For Heart Rate I used GoTo function to replace the blank cells with average heart rate 79.50
-  For BP I use GoTo function to replace the blank cells with average BP 117.55
-  For Diabetes, I used GoTo function to replace the blank cells with Unspecified
-  For Smoking I used GoTo function to replace the blank cells with Unspecified
-  For Blood Type I used GoTo function to replace the blank cells with blood Type A
-  For Age I used GoTo function to replace the blank cells with average age 26.
-  For Cholesterol i used GoTo function to replace the blank cells with average cholesterol 184.44
-  For weight i used GoTo function to replace the blank cells with average 69.97
---
#### After cleaning the raw data, below is a snippet of the cleaned data:

![](https://github.com/vinemadukpe/Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data./blob/main/MD01.png)

---
Haven cleaned the data, I created pivot table below showing the number of students in each blood type:
It's observed that there are more students with blood type A.

![](https://github.com/vinemadukpe/Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data./blob/main/MDS3.png) ![](https://github.com/vinemadukpe/Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data./blob/main/MDS33.png)

---
#### I Tabulated the number of students who said Yes, No, Unspecified to Smoking in the pivot table below:

![](https://github.com/vinemadukpe/Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data./blob/main/MDS4.png)

Below is the visual of the table above, from the insight the number of students who admitted to be smokers are far less and might not be considered fit for the sporting event. This means that the management still have a larger population of the students who are free from smoking and likely to be considered among the suspectible fit.

![](https://github.com/vinemadukpe/Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data./blob/main/MDS44.png)/ ![](https://github.com/vinemadukpe/Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data./blob/main/MDS444.png)

---
I created a pivot table of Average (Age, Cholesterol, BMI, Heart Rate, BP, Temperature) across the Gender as shown in the table below and from the visual, it can be observed that there's no significant differences in the Average (Age, Cholesterol, BMI, Heart Rate, BP, Temperature) between the Male and the Female. Also from this insights, the doctors can advise the management if the students in average are fit for the upcoming sporting event.

![](https://github.com/vinemadukpe/Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data./blob/main/MDS1.png) ![](https://github.com/vinemadukpe/Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data./blob/main/MDS11.png)

---
Below is the pivot table of average height and weight of both male and female students. Also, the visual of the data has shown that there's no significant difference between the female height and male height hence same average sports wears sizes will fit.

![](https://github.com/vinemadukpe/Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data./blob/main/MDS2.png) ![](https://github.com/vinemadukpe/Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data./blob/main/MDS22.png)

---
Finally, a pivot table of the number of students who are Diabetic, not Diabetic and unspecified were created as below with the visual Of course the greater number of students are not Diabetic from the insight in the visual below I believe this is due to the fact that the students are relatively young with average age of 26. The few that are Diabetic automatically aren't fit for the sporting event maybe they will be among others that would be cheering the ones that would participate.

![](https://github.com/vinemadukpe/Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data./blob/main/MDS5.png)  ![](https://github.com/vinemadukpe/Analysis-of-USM-University-Teaching-Hospital-Class-2020-Medical-Students-Data./blob/main/MDS55.png)

---
### Conclusion
From the insight above the management will be able to make an informed decision with a guide of a doctor and a fashion designer to determine how fit the students are, how many are free from diabetes, free from smoking and also the average size of outfit to purchase for the said sporting event.

---
