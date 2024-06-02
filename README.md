# Film Content Insights

![Film Content Insights](images/film%20content.jpg)

## Overview
This project analyzes current trends in the film industry by examining the performance of different genres at the box office. By investigating various datasets, including Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers, we aim to identify what types of films are currently most successful. This analysis will help in forecasting which film genres hold the most promise for profitability and audience engagement, thus guiding strategic decisions related to film production, marketing, and distribution.



## Business Problem
The film industry is highly competitive and continuously evolving, with varying audience preferences and technological advancements shaping market dynamics. Understanding which film genres are performing well at the box office can enable the newly established movie studio to allocate resources effectively, maximize returns, and expand its market presence. By leveraging detailed box office data, the studio can make informed decisions about which types of films to produce, potentially leading to increased profitability and audience acclaim.



## Data
The datasets include a mix of structured data from well-known film databases, covering extensive details about film genres, box office earnings, ratings, and audience feedback across several years. Each film is identified uniquely, allowing for precise tracking of its performance from release to international earnings. This comprehensive data enables an in-depth analysis of market trends, audience preferences, and financial outcomes associated with different film types.



## Methods
1. **Data Collection and Loading:**
    - Data was collected from multiple sources: Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers.
    - The datasets were loaded into Pandas DataFrames for processing.

2. **Data Cleaning and Preparation:**
    - Duplicate records were removed.
    - Missing values were handled appropriately.
    - Data was merged from different sources to create a comprehensive dataset.

3. **Exploratory Data Analysis (EDA):**
    - Initial analysis was conducted to understand the structure and content of the data.
    - Key metrics such as gross earnings, ratings, and audience feedback were calculated.

4. **Statistical Analysis:**
    - ROI (Return on Investment) was calculated for different genres and directors.
    - Correlations between runtime and profitability were analyzed.

5. **Visualizations:**
    - Bar plots and histograms were created to visualize the performance of different genres.
    - Comparative analysis was performed for Oscar-winning vs. non-Oscar-winning directors.

## Results
### ROI Based on Genre

![Genre ROI](images/genres.jpg)

- **Mystery and Horror** genres typically have lower production costs and high ROIs.
- **Animation, Adventure, and Sci-Fi** genres perform well globally with higher budgets.

### ROI Based on Directors

![Director ROI](images/director.jpg)
- Films directed by **Oscar-winning directors** have significantly higher domestic and worldwide ROIs compared to those directed by non-Oscar-winning directors.
- Directors like **Steven Spielberg, Ridley Scott, and David Fincher** lead in mean worldwide gross.

### ROI Based on Runtime
![Runtime ROI](images/runtime.jpg)
- **Short films (0-90 minutes)** offer the highest ROI both domestically and worldwide with lower production costs.
- **Mid-length films (91-150 minutes)** also perform well, especially in international markets.
- **Long films (151+ minutes)** have mixed results, with strong international performance but challenges in domestic profitability.

## Conclusions
1. **Genre-Specific Investment Strategies:**
    - Invest in low-cost, high-ROI genres like Mystery and Horror.
    - Continue high investment in globally appealing genres like Animation, Adventure, and Sci-Fi.

2. **Director Selection:**
    - Prioritize high-quality films with potential for critical acclaim by investing in top-tier talent.

3. **Runtime Considerations:**
    - Focus on producing short and mid-length films to maximize financial returns.

## Next Steps
- Further analysis to predict long stays and medical needs using detailed data modeling.
- Targeted marketing strategies based on genre and audience preferences.
- Development of a talent pipeline for nurturing new directors and actors.

## For More Information
- See the full analysis in the Jupyter Notebook or review this presentation.
- Tableau Dashboard available here: https://public.tableau.com/app/profile/neal.iyer/viz/FilmAnalysis_17173656924780/Dashboard1?publish=yes
- For additional info, contact Neal Iyer at neal.iyer88@gmail.co


