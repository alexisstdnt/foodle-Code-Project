# Foodle-Code-Project
Foodle! is a complete and working mobile-friendly website that combines structured qualitative and quantitative data and a knowledge-based recommender system to provide users with a list of restaurants in and around the Sydney CBD based on filter conditions of location, cuisine, meal-type and price range.

Please access foodle! via the following link: https://alexisstdnt.github.io/foodle-Code-Project/ 

Libraries used: 
- Axios. (2022). (Version 1.1.2)
- Lodash. (2020). (Version 4.17.20) 
- Xlsx. (2022). (Version 0.17.5)

Description of files 
- **index.html** contains the content and structure for the first page - its main purpose is to collect parameters that will be used to search the data
- **GetStarted.js** contains the Javascript methods that either serve as event handlers for controls on **index.html** or implement validation rules for the form
- **results.html** contains the content and structure for the second page - its main purpose is to display the results of matching restaurants 
- **Results.js** contains the Javascript methods that retrieve the items from localStorage, translates the data into a JSON object and parses the data. It also builds the html structure for the cards on the Results page.
- **web.css** contains the styling, layout, visual effects and background colour for the website 
- **Database.xlsx** is the data source 
