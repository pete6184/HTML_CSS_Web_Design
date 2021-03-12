# Web Design Homework - Web Visualization Dashboard (Latitude)

## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a website showing off the analysis we've done.

![Images/landingResize.png](Images/landingResize.png)

### Before You Begin

1. Create a new repository for this project called `Web-Design-Challenge`. **Do not add this homework to an existing repository**.

2. Clone the new repository to your computer.

3. Inside your local git repository, add your **html** files, as well as your **assets**, **Resources** and **visualizations** folders. Your `index.html` should be the landing page that the user first sees.

4. Push the above changes to GitHub or GitLab.

5. Push the above changes to GitHub.

6. Deploy to GitHub pages. 

## Latitude - Latitude Analysis Dashboard with Attitude

For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting [weather data](Resources/cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

For reference, see the ["Screenshots" section](#screenshots) below.

The website must consist of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. **Hint**: Bootstrap has a relatively easy way to [make tables responsive](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables) but it isn't the only way.  
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html). Or use an [online html table generator](https://www.tablesgenerator.com/html_tables).

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive such that at smaller screen sizes the navbar links are replaced by a sandwich menu. The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change). Again, bootstrap has [relatively easy ways](https://getbootstrap.com/docs/4.0/components/navbar/#toggler) to accomplish this, but it's not the only way.

Finally, the website must be deployed to GitHub pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

Ensure your repository has regular commits (i.e. 20+ commits) setting up your homework repository at the start and committing lots of small changes as you go. Also include a thorough README.md file.

### Considerations

* You have three options for choosing the content for your website: 
  * You may use the [weather data](Resources/cities.csv) from the Resources folder and pull the corresponding images from the included [assets folder](Resources/assets), 
  * you may use the included [weather data](Resources/citites.csv) and use your own images from the previous assignment, 
  * or you may choose another dataset entirely and generate your own images.
* You must use Bootstrap. This includes:
  * using the Bootstrap `navbar` component for the header on every page, 
  * the Bootstrap table component for the data page, and 
  * a Bootstrap grid for responsiveness on the comparison page.
* You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
* Be sure to use a CSS media query to control the behavioral states of the navigation menu.
* Be sure your website works at all window widths/sizes.
* Feel free to take some liberty in the visual aspects, but keep the core functionality the same.

### Bonuses

* Use a different dataset! The requirements above still hold, but make it your own.
* Use a Bootstrap theme or template to customize your website. You may use a source like [Start Bootstrap](https://startbootstrap.com/) or [Bootstrap Made](https://bootstrapmade.com/). Make it look snazzy, give it some attitude. And be sure you also meet all of the requirements listed above and in [the rubric](Unit_11_Web_Homework_Rubric.pdf).
* Add extra visualizations! The more comparisons the better, right?
* Use meaningful icons next to links in the header. One well-documented method is to use [Font Awesome](https://fontawesome.com/cheatsheet).
* Have visualization navigation on every visualizations page with an active state. See the screenshots below.

### Screenshots

This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

#### <a id="landing-page"></a>Landing page

Large screen:

![Landing page large screen](Images/landingResize.png)

Small screen:

![Landing page small screen](Images/landing-sm.png)
￼

#### <a id="comparisons-page"></a>Comparisons page

Large screen:

![comparison page large screen](Images/comparison-lg.png)

Small screen:

![comparison page small screen](Images/comparison-sm.png)

#### <a id="data-page"></a>Data page

Large screen:

![data page large screen](Images/data-lg.png)


Small screen:

![data page small screen](Images/data-sm.png)

#### <a id="visualization-pages"></a>Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:

![visualize page large screen](Images/visualize-lg.png)

Small screen:

![visualize page small screen](Images/visualize-sm.png)

#### <a id="navigation-menu"></a>Navigation menu

Large screen:
![nav menu large screen](Images/nav-lg.png)

Small screen:
![nav menu small screen](Images/nav-sm.png)
