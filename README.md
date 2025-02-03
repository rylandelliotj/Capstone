# Master of Public Policy Capstone Project Files
This is where you can find all the necessary files I used in creating my capstone project for my Masters project.
>Note: project requires some cleaning, as this represents early python work.
>Refactoring work, data scraping, and parallel processing are just some ways to improve upon this project.

## fire_area
This folder contains data collected from the National Wildfire Information Database.
I use the National Burn Area Composite data, since it combines best available data from a variety of sources. 
This is desirable, since provincial reporting can be inconsistent. 
I use the .dbf file to pull information on the area burned for each province, 
and then form there output a cleaned file 'national_clean' to use in the model.

## national
This is where you can find PM 2.5 data collected from Environment and Climate Change Canada.
Data is collected from a variety of sensors, and at hourly time intervals. 
I use an average daily value for the model. 
The national_smoke.ipynb file is responsible for creating outputs for target cities.

## CAPSTONE_signed.pdf
This is my final capsone report. In it, you can find a full explanation of the model used and the purpose of this research.

## final.ipynb
This is the model script used to create the distributed lag regressions.
