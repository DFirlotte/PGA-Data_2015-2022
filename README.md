# Analyzing 2022 Masters Data

Project Overview: Goals in this project are to analyze the data collected by the PGA and build a simple regression and evaluate the results

Data Understanding: This data includes player level information and results for each tournament through 2022. The features included numerical stats on how the player performed at the tournament.

Modeling and Evaluation: The data was filtered to only include the Masters 2022 stats, as this was the only year all the rows were filled in with the 'Shots Gained' stats. A simple regression model was built and fit between the position the player came in and the shots gained from tee to green stat. Below is a plot of the Ordinary Least Squares data with the best fit regression line.

![download](https://github.com/DFirlotte/PGA-Data_2015-2022/assets/93957112/c05b3dac-9a0b-4fdc-8458-4ff08c6861a9)

Conclusion: Based off of the OLS regression results, for every increase in postion (the worse the golfer finishes) their Shot Gained-Tee to Green stat will decrease by .060
