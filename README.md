# Movie Streaming During COVID-19 
---
![Quarantine image](chill_image.jpg)

## Introduction 
--- 

Going to the movies has been a staple in American culture for nearly a century, and while this date-night pastime isn't going anywhere anytime soon the landscape of film production is changing. With the emergence of streaming services such as Netflix, Hulu, or Amazon prime, big-time films are skipping the theater and coming right to our living rooms. The following analysis includes both films which were released at the box-office and on the couch - Microsoft would be remiss to avoid studying data from both mediums, especially in this cultural moment. It is hard to predict the changes that a global quarantine will bring across a multitude of industries but the film industry can't be excluded. While the following analysis is not exhaustive it provides interesting insights and provokes further curiosity.

## Data Use 
---

To perform this analysis I used information from the following sources to gain insight into the film industry:
<lo>
    <li> IMBD </li>
    <li> TMBD </li>
    <li> Rotten Tomatoes </li>
    <li> Wikpedia/Netflix </li>
    </lo>

## Methodology
---
<lo>
    <li> One way t tests</li>
    <li> Pearson's Correlation</li>
    <li> Mean </li>

## Navigating the repo
---

All the code is located within in the student.ipynb.

## Questions, Conclusions, Recommendations
---
### Questions
<ol> 
    <li> What are the top 100 profiting box office films? </li>
    <li> How do genre, feature length, production budget, and release date effect profit? </li>
    <li> What information can be gathered about Netflix original films?</li>
    <li> How do genre, release date, and feature length of Netflix original films compare to the top 100 profiting box office films?</li>
</ol>

### Conclusions
<ol> 
    <li> Production budget is predictive of greater profit (with a few exceptions) and runtime has little to no effect on box-office profit.</li>
    <li> Both genre and release date had a statistically significant effect on profit.</li>
    <li> For box-office movies the most common release months were in the summer (May/June/July) but the most profitable months were April, December, and June. </li>
    <li> The most common genres were Action, Animated/Family, and comedy (note: "No Data" held 40% of the genre data).
    <li> There is little to no information about Netflix original profit and production budget, however the following differences between direct-to-stream films and box-offices films were observed:
        <ol>
            <li> The mean feature length of Netflix Originals was 32 minutes shorter than box-offices films.</li>
            <li> The most common release months for Netflix Originals were September, October, and November.</li>
            <li> The most common genres of Netflix Originals were documentary, drama, and comedy.</li>
        </ol>
    </li>
</ol>

### Recommendations 
<lo> 
    <li> The strongest recommendation at this time is further research. It is apparent from this initial analysis that there are significant differences in the characteristics of original direct-stream films vs. box-office films. No assumptions are made about the origin of those differences at this time (viewer preferences, investor preferences, budget allowance, experimentation, etc.) but this subject is worth further investigation. Also, the absence of information about viewership and production budgets make understanding these differences challenging; this information would be essential to inform production of a new streaming service. Further, measuring "profit" for individual productions is a unique undertaking but would be invaluable information - it is recommended Microsoft considers creating a standardized way to measure this. Finally, it would be of interest to study the changes in viewer preferences during this forced home-streaming only quarantine.
    </li>
</lo>

### Future Recommendations to Myself
---
<lo>
	<li> Use an SQL database to compile the csv files from the start</li>
	<li> Use several different ipynbs to document the process</li>
	<li> Make a more extensive plan of the analysis prior to executing</li>
    <li> Continue to review dataframe manipulation (concat, merge, etc.) and data visualization techniques</li>
</lo>

## Cheers!