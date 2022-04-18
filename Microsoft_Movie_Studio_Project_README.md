# Microsoft Movie Studio Project

**Author**: Nat Berryman

## Overview

The head of Microsoft's new movie studio requires data analysis to assist in his decision making on what movies to create. Multiple data sources have been used from Box Office Mojo and IMDB. These data sets were cleaned to ensure the data was analysied effictively to produce results and recommodenations. It was determined that BV was the most successful movie studio while Action/Adventure/Amination genres were the most popular amongst movie-goers. It was also determined the best release month for highest performing movies was June and November. Follwing these results the below actions are strongly recommended.

1. Explore partnership opportunities with existing production studios e.g. Disney partnering with Sony for the Spider-Man movies
2. Creating Action/Adeventure or Animated Adventure movies
3. Ensuring the release dates for the films in June or November.

## Business Problem

The business problem that I set out to solve was, how can Microsoft's venture into the movie making industry be successful?

In order to solve this problem, I intended to find answer for the following questions:

What are the highest grossing production studios?
What is the highest grossing movie genres?
What is the most successful release patterns?

***
Questions to consider:
* What are the business's pain points related to this project?
* How did you pick the data analysis question(s) that you did?
* Why are these questions important from a business perspective?
***

## Data

The data used for this analysis was the Title Basics and Title Ratings from IMDB, Movie Gross from Box Office Mojo and Movie Budgets from The Numbers. The sets represent the total movies number of movies released over a determined timeframe, the titles and production studios, the rating scores, primary and sub-genres along with the domestic and world gross revenue. It was identifed that these sets had the data required to make meaningful recommendations to the head of Microsofts movie studio

***
Questions to consider:
* Where did the data come from, and how do they relate to the data analysis questions?
* What do the data represent? Who is in the sample and what variables are included?
* What is the target variable?
* What are the properties of the variables you intend to use?
***

## Methods

I started by merging all of the data sets into one dataframe which left 1413 entries. Once merged I dropped irrelevant columns and removed duplidate movie titles. Then I split out the genres into primary genre columns and sub-genre columns and converted the dates into columns for easier evaluation. After I determined the averagerating and numvotes columns were not relevent, I also removed them. This left me with a workable dataset to assist in making suitable recommendations to the head of Microsfots movie making department.

***
Questions to consider:
* How did you prepare, analyze or model the data?
* Why is this approach appropriate given the data and the business problem?
***

## Results

To assist in making the solid recommendations to Microsoft I grouped together the most profitable movie studios, the highest grossing genres and finally the highest grossing release dates. Initially my thoughts would indicate a higher rating would correlate with high gross but this was deemed incorrect. Due to this I removed the rating columns as they were unnecessary to the final output. The results were appropraite to help solve the business problem as it identified the most profitable established movie production company to approach, the highest grossing genres to develop along with the release dates.

***
Questions to consider:
* How do you interpret the results?
* How confident are you that your results would generalize beyond the data you have?
***

Here is an example of how to embed images from your sub-folder:

### Visual 1
![graph1](./images/viz1.png)

## Conclusions

Evaluation
From the published results it was clear that Microsoft would benefit from;

1. Approaching the Top 5 movie productions to explore partnership opportunities.
2. Primarily explore developing Action/Adventure movies followed by animated adventure movies.
3. Releasing the movies June or November to fit in with the current box office release patterns.

The evaluation has identified profitable movie studios and high gross revenue returns however this would reqiure expensive investment. It is suggested that Microsoft would benefit from further data analyis into smaller budget and/or foreign film markets as this may still yield attractive profits.

***
Questions to consider:
* What would you recommend the business do as a result of this work?
* What are some reasons why your analysis might not fully solve the business problem?
* What else could you do in the future to improve this project?
***

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact **name & email, name & email**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md
├── Microsoft Movie Studio Project.ipynb
├── Microsoft Movie Studio Project Presentation.pdf
├── data
└── images
```
