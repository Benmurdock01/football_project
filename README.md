This repo contains several .csv files from college football seasons.

In the data folder, there are the orginal .csv files I downloaded.

I then wrote the 'dataframe_cleaner.ipynb' to combine and clean the .csv files.

In the 'dataframe_cleaner.ipynb' script you will fine a 4 code chunks. 
- The first is the chunk that contains all the libraries.
- The second is the chunk that I used to combine all the csv files into one file
    I had to add a 'season' column to keep track of which line was from what season.
    This combines dataframe is saved as 'combined_football_data.csv'
- The third was a quick line just to check what type of data python recongized the entries as.
- The fourth is code to get ride of all the data after 2020. After looking at the
    'combined_football_data.csv', I saw that most of the data afte 2020 was missing. I am
    not sure if this is because of Covid of outdated record keeping. Either way I didn't want
    it in my final data set, incase the missing entires would throw off my future use of this
    data. I named the cleaned data set 'filtered_football_data.csv'.

My end result was a .csv file with complete college football stats from 2013 to 2020.