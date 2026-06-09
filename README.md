# MessyMovieMending
Transformed a messy, semi-colon-delimited Kaggle dataset into a polished, usable resource using Excel. I tackled inconsistent formatting, corrected date structures, and validated entries against IMDB. This project highlights the precision required to salvage "rough" data while balancing manual cleanup with the risks of altering historical records.

## Before
<img width="1558" height="619" alt="image" src="https://github.com/user-attachments/assets/29634a1a-5c0a-4fa3-ae8e-d719538dcbe8" />

## After
<img width="1493" height="701" alt="image" src="https://github.com/user-attachments/assets/b9a79706-4c12-4028-a35a-ba27ad2554f2" />


# Finished Product
- A clean dataset

# Programs Used
- Excel

# Goals
- To restore the dataset to a usable state and fill in missing data where applicable.

# Cleaning Process 
This dataset was rough! Combined values with a common semicolon separator but not always in the same order and not all in the same column required a careful hand. I primarily utilized text split, text before, text after, if statements to run logical validation formulas, and filters to uncover especially dirty details. I also used “find and replace” to remove the large number of decimals in the votes and format painter/manual corrections on several of the dates. For details I couldn’t validate by eye alone, I searched IMDB and referenced that. This data appears to be sourced in Italian so many of the release dates are Italy based. I didn’t go through and correct all of the missing data, but I did do a few here and there when I was verifying dates. Ideally, I would have done 0 additions/validating as it can cause data problems down the road (for example, this data was sourced in xyz year and represents xyz numbers not current day numbers. Ideally, in a real setting, I’d have a specific request or question I’m chasing, and I can allocate my resources towards the data pertaining specifically to that question instead.  

# Opportunities
In addition to being rough, I realized I made an error in cleaning and had some data loss. Some of the movies have 3 genres and those extra/not-extra columns created difficulty when using the text splits/text after formulas. Definitely a lesson learned and something to keep in mind when cleaning in the future!  
