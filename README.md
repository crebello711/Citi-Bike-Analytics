# Citi-Bike-Analytics

## Steps to Analysis(Download, extract, cleaned data, import to Tableau)
* Downloaded the zipped files from Jan 2018- Sep 2022 from [City Bike Data](https://ride.citibikenyc.com/system-data)
* By Using the Windows PowerShell wrote a script to extract 57 csv files directly to a folder. [Extraction Process](https://stackoverflow.com/questions/28448202/i-want-to-extract-all-zip-files-in-a-given-directory-in-temp-using-powershell)
* Imported data from Jan 2018 to Sep 2022 but data analysis performed only on the data captured from `Feb 1st 2021 to Sep 30th 2022`

## Phenomenon Visualization
* How many trips have been recorded in total during the chosen period by duration?
  
  `The tree chart shows the trip duration records in minutes per each ride_id.` 
  ![image](https://user-images.githubusercontent.com/107435952/200425380-23f2559f-feaa-4702-9153-7bafc6476f5b.png)


* What are the peak hours when bikes are used during the summer months and winter months?
  
  `The peak hour time of the day for member ride is the highest around 8 am in the morning and 6 pm in evening. Well these two time points are expected to be high since they are the peak hours for travelling daily to work. A similar trend is also observed in winter months except that the winter reduce the moment of riders so we see a decline in the member count for winter months.`
  ![image](https://user-images.githubusercontent.com/107435952/200427680-ac063705-1f9e-40be-8835-5fcc32df0721.png)

* Top 10 stations and bottom 10 stations in the city for starting a journey?
`Top 10 stations for starting journey`
![image](https://user-images.githubusercontent.com/107435952/200428077-06418647-32a7-44a3-bc12-8bf8a0fa3c3d.png)


