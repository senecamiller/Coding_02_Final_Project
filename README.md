# Coding_02_Final_Project

# Seneca F. Miller
# STUDENT ID: 2405932

# Meidum Article Link: https://medium.com/@senecawyse/webscraping-in-python-an-analysis-of-data-scraped-from-plane4you-com-53ed52ff2872

# The Web Scraping 02 final project showcases my ability to work with an HTML-based data source. I created a function that takes a single plane listing link and returns the information associated with that link. I scraped data from all seven pages containing multiple listings and saved the information in a DataFrame which was saved as final_df.csv. This data was cleaned and processed and then three visualizations were created from the cleaned data. 

# This repository contains six files in addition to the README. The file 'Create_DataFrame.ipynb' includes the code for scraping the plane4you.com website and saves the scraped information in the DataFrame final_df.csv. This saved DataFrame is accessed at the beginning of the 'Clean_DataFrame.ipynb' file. A copy of final_df.csv is created so the cleaning can be done while keeping the original DataFrame intact. The cleaned data was saved in the DataFrame final_df_cleaned.csv which was accessed in the three visualization files ('Visualization_01.ipynb', 'Visualization_02.ipynb', 'Visualization_03.ipynb'). The file 'Total_Code.ipynb' combines the above five documents. It is meant for a full overview of the data, but not necessarily intended to be run. It will run without errors, but it will likely overwrite 'final_df.csv' which will alter the data in 'final_df.csv' and, consequently, change the inputs, and therefore outputs, for the three charts. For a more thorough description of this dataset and the web scraping, cleaning, and analytics involved please read my medium article with the link at the top of this README. 

# Thank you to Professor Mihlay Orsos for his support of this project and to Central European University for all they do for the Business Analytics MS program.
