java c
ECOM 2001 Term Project Description
Due 30 September at 9:00AMAWST
IntroductionThe aim of this project is to prepare, evaluate and analyse stock market data and to recommend an optimal portfo- lio consisting of two stocks. You have been assigned three stocks, all three must be included in the analysis which works towards your recommendation of a final optimal portfolio. The project requires a deep understanding of both the statistics and the mathematics components of this unit. It is recommended that you work on this on a weekly basis.
YOU MUST USE THE STOCKS ASSIGNED TO YOU. Any deviation from the assigned stocks will results in a grade of zero.Refer to the rubric at the end of this document to understand how this assessment will be graded. In particular, note that all figures need to be numbered and labelled, and you need to include all the steps to involved with arriving at each of your answers.Your final report should be a pdf document. An RMarkdown document to get you started is available on the unit Blackboard site. Show all of your coding by keeping echo  =  TRUE. Make sure to update your name and student ID in theYAML of the document.
You are NOT ALLOWED to engage any AI-assistive platforms to complete this assessments, unless you are told otherwise (in 2 questions below).
1    Import Data (2 points)
Import the adjusted stock prices for the three stocks which you have been assigned.  See the Markdown file for hints.
2   The Analysis
2.1    Plot prices over time (4 points)
Plot the prices of each asset over time separately.
Succinctly describe in words the evolution of each asset over time. All axes and figures have to be properly labeled and described. (limit: 100 words for each time series).
2.2    Calculate returns and plot returns over time (4 points)
Calculate the daily percentage returns of each asset using the following formula:

Where Pt is the asset price at time t. Then plot the returns for each asset over time.
2.3    Histogram of returns (6 points)
Create a histogram for each of the returns series. You have to explain your choice of bins.
You will need to carefully label all axes and figures.
You are expected to: - Write a short paragraph to describe the trend of each time series; - Discuss the formula to calculate the bins.
(Hint: Discuss the formula you use to calculate the bins)
2.4    Summary table of returns (5 points)
Report the descriptive statistics in a single table which includes the mean, median, variance, standard devia- tion, skewness and kurtosis for each series. All tables need to be correctly labeled.
What conclusions can you draw from these descriptive statistics?
2.5   Are average returns significantly different from zero? (6 points)Under the assumption that the returns of each asset are drawn from an independently and identically dis- tributed normal distribution, are the expected returns of each asset statistically different from zero at the 1% level of significance?
Part 1: Provide details for all 5 steps to conduct a hypothesis test, including the equation for the test statistic. All steps have to be shown and this part has to be repeated for each hypothesis test. (1 points)
Part 2: Calculate and report all the relevant values for your conclusion and be sure to provide an interpretation of the results. (Hint: you will need to repeat the test for expected returns of each asset) (3 points - one for each stock)Part 3: If you would have done this question using Chat-GPT, what answer will you get?  (hints: you will need to describe how you prompt the question in Chat-GPT to guide t代 写ECOM 2001 Term Project DescriptionWeb
代做程序编程语言he answer (1 point), would expect your answer to be different or similar to your answer above and provide your rationale? (1 point))
2.6   Are average returns different from each other? (7 points)
Assume the returns of each asset are independent from each other. With this assumption, are the mean returns statistically different from each other at the 1% level of significance?
Provide details for all 5 steps to conduct each of the hypothesis tests using what your have learned in the unit. All steps have to be shown and this part has to be repeated for each hypothesis test. (2 points)
Calculate and report all the relevant values for your conclusion and be sure to provide and interpretation of the results. (Hint: You need to discuss the equality of variances to determine which type of test to use.) (3 points)
If you have a chance to engage Chat-GPT, how would you approach this question? That is, you need to clearly lay out ALL STEPS that you would ask the question to Chat-GPT. (1 points)Now, compare your answer to Chat-GPT, why do you think your answer is different or similar? Please attach a picture of the screenshot of the answer you have got from Chat-GPT. What do you learn from this exercise?  (1 points)
2.7    Correlations (2 points)
Calculate and present the correlation matrix of the returns. Discuss the direction and strength of the correlations.
2.8    Testing the significance of correlations (2 points)
Is the assumption of independence of stock returns realistic?Provide evidence (the hypothesis test including all 5 steps of the hypothesis test and the equation for the test statistic) and a rationale to support your conclusion. All steps have to be shown and this part has to be repeated for each hypothesis test.
2.9   Advising an investor (12 points)
Suppose that an investor has asked you to assist them in choosing two of these three stocks to include in their portfolio. The portfolio is defined by
r = w1 r1 + w2 r2Where r1 andr2 represent the returns from the first and second stock, respectively, and w1 and w2 represent the proportion of the investment placed in each stock. The entire investment is allocated between the two stocks, so w1 + w2  = 1.
The investor favours the combination of stocks that provides the highest return, but dislikes risk. Thus the investor’s happiness is a function of the portfolio, r:
h(r) = E(r) − Var(r)
Where E(r) is the expected return of the portfolio, and Var(r) is the variance of the portfolio.
Given your values forE(r1 ), E(r2 ), Var(r1 ), Var(r2 ) and Cov(r1 , r2 ) which portfolio would you recommend to the investor? What is the expected return to this portfolio?Provide evidence to support your answer, including all the steps undertaken to arrive at the result. You will need to solve the optinmisation problem using pen and paper, and you need to typeset your answer. You can then scan as picture to attach here as your answer. You can show the summary statistics using the coding learned in class, but the optimisation problem has to be solved by hand.
You will need to get your instructors to validate your identity of your work by asking them to sign your work when you complete it. Without their validation, you will automatically get a zero for this question.Note: You will need to typeset your answer. Then, you need to put your name and student ID number on every page (and side) of your work. You will have the instructor to validate your information by signing your answer sheet. Then, you can scan the answer as picture(s) and embed it here as your answer.



         
加QQ：99515681  WX：codinghelp
