# Michelin Star Restaurant Search Engine  
This project explores the process of creating a search engine for Michelin-starred restaurants on a website. In this specific project, [this](https://guide.michelin.com/en/it/restaurants) website has been used.  

**_NOTE:_** _This is not an app but an explanation and implementation of how we can create a search engine from scratch._   

---  
The repository consists of the following:  
1. **_notebook.ipynb_**  
   - Webscraping to collect URLs of all pages listing the restaurants and store them.  
   - Then each URL page is downloaded and saved as a .html file.  
   - Then each HTML file is parsed to collect relevant data for each restaurant and stored in a .tsv file.  
   - Search Engine implementation and improving upon it as we move on.  
   - Creation of an interactive map displaying all searched restaurants.
2. **_FILES_**  
   This folder further consists of two files:
   - _michelin_restaurants_urls.txt_: URLs of each page of the website stored in a .txt file.  
   - _italian_restaurants_map.html_: This .html file when opened in a browser shows an example of the interactive map in case you cannot see it in the notebook.


I have not added the .html files for all the URLs as well as the sample .tsv file due to storage constraints.
