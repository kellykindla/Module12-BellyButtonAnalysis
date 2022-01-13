# Belly Button Analysis 
## Module 12 

## Project Overview 
### Purpose of Module 12 
The purpose of this module was to build on our knowledge of JavaScript to manipulate, parse, and transform data. We also expanded our knowledge of D3.json and can now collect external data from CSV files and web APIs. We were introduced to Plotly, a data visualization library, and utilized its components to create data visualizations that are not only easy to understand, but interactive. 

### Overview of Assignment 
For this assignment, we were presented with a json file containing bacterial data collected from each volunteers belly button. The data collected contained an array of the participants unique IDs, an array of metadata that contained objects with the demographic information for each participant, and an array of samples that contained the bacterial data collected for each participant. We used functional programming in JavaScript to manipulate the data so we could visualize each participants results based on the participant ID selected from a dropdown menu. We created functions to recognize when the selected sample ID has changed and used that information to create the corresponding demographics table and charts. The demographics table and gauge are build on the metadata array while the bar and bubble charts are based on the samples array. After creating each chart, we build our index.html file with bootstrap components to properly display the information in an interactive webpage. I further used CSS components to alter the html page to my liking. 

### Resources 
  - Data for the project came from 
    - **_samples.json_**
  - VS Code 1.62.1
  - Google Chrome 
  - Command-line interface 
  - Github
  - Bootstrap 
  - Plotly
  - Other resources:
    - [For Gauge](https://plotly.com/javascript/gauge-charts/)
    - [For Gauge Ticks](https://plotly.com/javascript/tick-formatting/) 
    - [For Layout Properties](https://plotly.com/python-api-reference/generated/plotly.graph_objects.Layout.html)
    - [For Bubble Chart](https://plotly.com/javascript/bubble-charts/#hover-text-on-bubble-charts)
    - [For Matplotlib Colors](https://matplotlib.org/3.1.0/gallery/color/named_colors.html)
    - [For Color Scheme](https://plotly.com/python/builtin-colorscales/)
    - [For NavBar](https://mdbootstrap.com/docs/standard/extended/jumbotron/#)
    - [Jumbotron Image](https://www.independent.co.uk/news/science/resistant-anti-biotic-bacteria-treatment-b1933940.html) 

### Results 
The end result of the assignment is an interactive dashboard that researchers and participants can use to see what bacteria live in their bellybuttons. The user can select an ID from the dropdown menu and the corresponding bacterial data will be displayed in the demographic table, bar chart, gauge, and bubble chart. 

To complete the challenge, we were asked to customize our webpage. The customizations I made were: 
  1. Added an image to the jumbotron. 
  2. Created CSS style sheet that explicitly states the background color and font for the body of the webpage.
  3. Added more information about the project as a paragraph on the webpage 
  4. Added a fixed navigation bar that allows the user to refresh the page or jump to the bar or bubble chart on the page. 

The following image displays the navigation bar, jumbotron, and paragraph of the webpage: 
<img width="1167" alt="Jumbotron" src="https://user-images.githubusercontent.com/92558842/149363473-edbf7517-109c-410e-8f47-2f53a8db262d.png">


The next two images show the charts created for participant 940 and 1242: 
<img width="908" alt="P940" src="https://user-images.githubusercontent.com/92558842/149363600-ff7cceeb-a292-43dc-83e1-754f3b70de26.png">
<img width="923" alt="P1242" src="https://user-images.githubusercontent.com/92558842/149363619-9df8f5aa-2783-4618-bf07-9f0eda405e9f.png">
