# Country Vaccination Statistics Covid-19 

I implemented the code to fill the missing data in daily_vaccinations column per country with the minimum daily vaccination number of relevant countries. Kuwait does not have any valid vaccination number yet, so i filled it with zero. 

Then i found median values for each country and i found the maximum one by using groupby and max() functions.

At last i used groupby function to get every specified day in the dataset and made a summation of every countries daily vaccination data for specific days.

You can find the code within the master branch. I hope you like it.

<img width="1198" alt="Ekran Resmi 2021-03-24 02 42 08" src="https://user-images.githubusercontent.com/79477750/112232975-99c19000-8c4a-11eb-80ea-d46f4bd43cd4.png">
