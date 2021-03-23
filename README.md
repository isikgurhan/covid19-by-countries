# Country Vaccination Statistics Covid-19 

I implemented the code to fill the missing data in daily_vaccinations column per country with the minimum daily vaccination number of relevant countries. Kuwait does not have any valid vaccination number yet, so i filled it with zero. 

Then i found median values for each country and i found the maximum one by using groupby and max() functions.

At last i used groupby function to get every specified day in the dataset and made a summation of every countries daily vaccination data for specific days.

You can find the code within the master branch. I hope you like it.
