# Web Design Homework - Web Visualization Dashboard (Latitude)

## Requirements & Summary
For this assignment we used a code editor (I used Visual Studio Code) to write our code, launched the website through the code editor's live server, and then 'hosted' the web page via GitHub-pages.

This assignment was focused on taking information gathered from a previous assignment (WeatherPy) and displaying the information into a webpage. This allows the information to be distributed to a larger number of end users who might not be as familiar with code editors or other analytics programs.

## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a website showing off the analysis we've done.

For this homework we created a visualization dashboard website using the visualizations we created in a past assignment. Specifically, we plotted from the API WeatherPy assignment.

In building this dashboard, I created individual pages for each plot and a means by which individuals can navigate between them. These pages contain the visualizations and their corresponding explanations. The web pages are also responsive to the screen size. This was achieved using breakpoints and CSS styling.

### Website Requirements

The website consists of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot and clicking an image should take the user to that visualization.

![landing_page](https://user-images.githubusercontent.com/74940976/118374670-53b1ea00-b572-11eb-84f4-c6dbbe317a5a.PNG)

* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.

![maxTemp_page](https://user-images.githubusercontent.com/74940976/118374677-5b718e80-b572-11eb-84f4-ff3ce11ab9a5.PNG)

![humidity_page](https://user-images.githubusercontent.com/74940976/118374681-5f051580-b572-11eb-8308-73fab93677ee.PNG)

![cloudiness _page](https://user-images.githubusercontent.com/74940976/118374687-62989c80-b572-11eb-8fda-43d59a752ae8.PNG)

![windSpeed_page](https://user-images.githubusercontent.com/74940976/118374689-64faf680-b572-11eb-9a73-c1b28a15e0b6.PNG)

* A ["Comparisons" page](#comparisons-page) that:
  * Contains all the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.

![comparison_page](https://user-images.githubusercontent.com/74940976/118374693-69271400-b572-11eb-8b67-e9818166b465.PNG)

* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.

![data_page](https://user-images.githubusercontent.com/74940976/118374698-6fb58b80-b572-11eb-8970-137596638d69.PNG)


## Responsiveness

![breakpoint](https://user-images.githubusercontent.com/74940976/118374706-7d6b1100-b572-11eb-9afb-f40ffc594ceb.PNG)
