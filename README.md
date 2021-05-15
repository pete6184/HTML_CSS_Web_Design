# Web Design Homework - Web Visualization Dashboard (Latitude)

## Requirements & Summary
For this assignment we used a code editor (I used Visual Studio Code) to write our code, launched the website through the code editor's live server, and then 'hosted' the web page via GitHub-pages.

This assignment was focused on taking information gathered from a previous assignment (WeatherPy) and displaying the information into a webpage. This allows the information to be distributed to a larger number of end users who might not be as familiar with code editors or other analytics programs.

## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a website showing off the analysis we've done.

For this homework we created a visualization dashboard website using the visualizations we created in a past assignment. Specifically, we plotted from the API WeatherPy assignment.

In building this dashboard, I created individual pages for each plot and a means by which individuals can navigate between them. These pages contain the visualizations and their corresponding explanations.

### Website Requirements

The website consists of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot and clicking an image should take the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
