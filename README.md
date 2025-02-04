# Microsoft Movie Industry Recommendations

**Author**: Jasper Chen

## Overview

Microsoft wants to enter the movie industry.  It needs some recommendations to start.

## Business Problem

Find some of the best genres, actors, and writers.

***
Questions to consider:
* What are the business's pain points related to this project?

Cleaning comma delimited genres. Coverting comma delimited strings to numbers.

* How did you pick the data analysis question(s) that you did?

Genres, actors, writers seem like obvious choices.

* Why are these questions important from a business perspective?

No one wants to see unpopular genres, bad actors, with bad content.

***

## Data

Describe the data being used for this project.

IMDB data for movie genres


***
Questions to consider:
* Where did the data come from, and how do they relate to the data analysis questions?

Genre data from IMDB.

Revenue data from Box Offic Mojo.

Budget data from The Numbers.

* What do the data represent? Who is in the sample and what variables are included?
* What is the target variable?
* What are the properties of the variables you intend to use? 

absolute profit = domestic revenue - budget
ROI = (absolute profit / budget) * 100
***

## Methods

Describe the process for analyzing or modeling the data. For Phase 1, this will be descriptive analysis.

***
Questions to consider:
* How did you prepare, analyze or model the data?
* Why is this approach appropriate given the data and the business problem?
***

## Results

Present your key results. For Phase 1, this will be findings from your descriptive analysis.

***
Questions to consider:
* How do you interpret the results?
* How confident are you that your results would generalize beyond the data you have?
***

Here is an example of how to embed images from your sub-folder:

### Genre Histogram
![genre histogram](./img/genre_hist.png)

## Conclusions

Within the past 10 years, there have been a lot of action and adventure movies.

### Profit vs Genre
![profit vs genre](./img/profit_vs_genre.png)

### Genre Conclusion
The most profitable genres within the past 10 years

By absolute profit: Animation, Sci-fi

By ROI: Horror, Mystery

### Profit vs Actor
![profit vs actor](./img/profit_vs_actor.png)

### Conclusion
The most profitable actors

Best absolute profit: Denzel Whitaker, Matty Cardarople

Best ROI: Ionut Grama, Corneliu Ulici
### Profit vs Writer
![profit vs writer](./img/profit_vs_writer.png)

### Conclusion
The most profitable living movie writers within the past ten years

Simon Rich writes the best movies based on absolute profit.

Scott Beck writes the best movies based on ROI.
# Final Conclusion
Create a horror/mystery written by Scott Beck with actors Ionut Grama, Corneliu
Ulici.

***
Questions to consider:
* What would you recommend the business do as a result of this work?

Create a horror/mystery written by Scott Beck with actors Ionut Grama, Corneliu
Ulici.

* What are some reasons why your analysis might not fully solve the business problem?

The genre, actor, and writer might not match each other.


Market saturation might make it difficult to start.
* What else could you do in the future to improve this project?

Match writers to their proficient genre.
***

## For More Information

Please review our full analysis in [our Jupyter Notebook](./project.ipynb) or our [presentation](./Micrsoft Movie Proposal.pdf).

For any additional questions, please contact **Jasper Chen jasperschen@gmail.com**

## Repository Structure

```
├── README.md                           <- The top-level README for reviewers of this project
├── Micrsoft Movie Proposal.pdf         <- PDF version of project presentation
└── img                                 <- Both sourced externally and generated from code
├── src
│   ├── project.ipynb               <- .py script to create finalized versions of visuals for project
|── zippedData                                 
    ├── bom.movie_gross.csv.gz          <- Box Office Mojo movie revenue data
    ├── im.db.zip                       <- IMDB data (for genres, actors, writers)
    ├── tn.movie_budgets.csv.gz         <- The Numbers movie budget data
```
