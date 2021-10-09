# Web-Design-Challenge
## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

## Latitude - Latitude Analysis Dashboard with Attitude

For this project I create a visualization dashboard website using visualizations from a  past assignment. Specifically, we'll be plotting [weather data].

In building this dashboard, I create individual pages for each plot and a means by which to navigate between them. These pages will contain the visualizations and their corresponding explanations. I also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

The website must consist of 7 pages total, including:

* A [landing page] containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages], each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page] that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
  * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page] that:
  * Displays a responsive table containing the data used in the visualizations.
  * The table must be a bootstrap table component.
  * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. 

* The website must, at the top of every page, have a navigation menu that:
  * Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
  * Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
  * Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
  * Is responsive (using media queries).

* Finally, the website must be deployed to GitHub pages.
