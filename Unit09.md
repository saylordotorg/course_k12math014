**Unit 9: Regression and Correlation** <span id="9"></span> 
*Up to this point we have studied univariate data. This type of data
studies one item, such as weight loss or IQ or miles per gallon. But in
Unit 9, we expand our study of statistics to include bivariate data,
which is the relationship between two numerical measures. These might
include the relationship between calories eaten and pounds lost, or the
number of hours studied and the score on an exam. The study of bivariate
data allows us to see if knowledge of one variable (the number of
registered boats in Florida, for example) can predict the value of
another variable (the number of manatees killed) with some degree of
accuracy.*  
    
 *In Unit 9, we will learn how to create a scatterplot from our data and
then use sophisticated mathematical techniques to determine the best
linear equation that relates the two variables. We will calculate the
correlation between the variables and test hypotheses about the strength
of the linear relationship between them.*

**Unit 9 Time Advisory**  
Completing this unit should take approximately 11 hours and 40
minutes.  
  
 ☐    Subunit 9.1: 4 hours and 5 minutes  
  
 ☐    Subunit 9.2: 4 hours and 5 minutes  
  
 ☐    Subunit 9.3: 2 hours and 30 minutes  
  
 ☐    Unit 9 Assessment: 1 hour

**Unit9 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:
-   Understand the concepts of bivariate data and correlation and the
    use of scatterplots to display bivariate data.  
      
-   Calculate the linear correlation coefficient and coefficient of
    determination of bivariate data, using technology tools to assist in
    the calculations.  
      
-   Calculate and graph the least-squares regression line, and use the
    linear equation for prediction.  
      
-   Calculate and plot residuals and test for linearity.  
      
-   Make inferences about regression models and assumptions, including
    hypothesis testing for linear relationships.

Standards Addressed (*Common Core and AP*):
-   [CCSS.Math.Content.HSS-ID.B.6](http://www.corestandards.org/Math/Content/HSS/ID/B/6)  
      
-   [CCSS.Math.Content.HSS-ID.B.6a](http://www.corestandards.org/Math/Content/HSS/ID/B/6/a)  
      
-   [CCSS.Math.Content.HSS-ID.B.6b](http://www.corestandards.org/Math/Content/HSS/ID/B/6/b)  
      
-   [CCSS.Math.Content.HSS-ID.B.6c](http://www.corestandards.org/Math/Content/HSS/ID/B/6/c)  
      
-   [CCSS.Math.Content.HSS-ID.C.7](http://www.corestandards.org/Math/Content/HSS/ID/C/7)  
      
-   [CCSS.Math.Content.HSS-ID.C.8](http://www.corestandards.org/Math/Content/HSS/ID/C/8)  
      
-   [CCSS.Math.Content.HSS-ID.C.9](http://www.corestandards.org/Math/Content/HSS/ID/C/9)  
      
-   [CCSS.ELA-Literacy.RST.11-12.1](http://www.corestandards.org/ELA-Literacy/RST/11-12/1/)  
      
-   [CCSS.ELA-Literacy.RST.11-12.2](http://www.corestandards.org/ELA-Literacy/RST/11-12/2/)  
      
-   [CCSS.ELA-Literacy.RST.11-12.3](http://www.corestandards.org/ELA-Literacy/RST/11-12/3/)  
      
-   [CCSS.ELA-Literacy.RST.11-12.4](http://www.corestandards.org/ELA-Literacy/RST/11-12/4/)  
      
-   AP I.D.1  
      
-   AP I.D.2  
      
-   AP I.D.3  
      
-   AP I.D.4  
      
-   AP I.D.5  
      
-   AP IV.A.8  
      
-   AP IV.B.6  
      
-   AP IV.B.7

**9.1 Scatterplots and Linear Correlation** <span id="9.1"></span> 
*In this subunit, we are introduced to the idea of bivariate data, which
is a relationship between two variables, such as height and shoe size,
mother’s IQ and daughter’s IQ, or number of hours spent watching
television versus number of hours spent doing homework.*  
    
 *We will look at the strength of these kinds of relationships by use of
the linear correlation coefficient. For height and shoe size, it sounds
reasonable to think that the taller a person is, the larger the shoe
size. But there are some short individuals with large shoe sizes, and
there are some tall people with small shoe sizes, so the relationship is
not perfect. We will learn how to calculate a value that will measure
how strong the relationship is between two numerical variables*

-   **Explanation: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 9.1: Scatterplots
    and Linear Correlation”; partially adapted from David Lane’s *Online
    Statistics Education: A Multimedia Course of Study* and CK-12:
    *Advanced Probability and Statistics***
    Link:The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s *Advanced
    Probability and Statistics*: [“Section 9.1: Scatterplots and Linear
    Correlation”](http://www.saylor.org/site/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
      
     Instructions: Read Section 9.1. The manual calculation of the
    correlation coefficient is cumbersome. You will want to use your
    calculator to verify that the manual calculations shown in the text
    are correct.  
      
     Reading this section and taking notes should take approximately 1
    hour and 30 minutes.  
      
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-ID.B.6a](http://www.corestandards.org/Math/Content/HSS/ID/B/6/a)
    -   [CCSS.Math.Content.HSS-ID.B.6b](http://www.corestandards.org/Math/Content/HSS/ID/B/6/b)
    -   [CCSS.Math.Content.HSS-ID.B.6c](http://www.corestandards.org/Math/Content/HSS/ID/B/6/c)
    -   [CCSS.Math.Content.HSS-ID.C.7](http://www.corestandards.org/Math/Content/HSS/ID/C/7)
    -   [CCSS.Math.Content.HSS-ID.C.8](http://www.corestandards.org/Math/Content/HSS/ID/C/8)
    -   [CCSS.Math.Content.HSS-ID.C.9](http://www.corestandards.org/Math/Content/HSS/ID/C/9)
    -   [CCSS.ELA-Literacy.RST.11-12.2](http://www.corestandards.org/ELA-Literacy/RST/11-12/2/)
    -   [CCSS.ELA-Literacy.RST.11-12.3](http://www.corestandards.org/ELA-Literacy/RST/11-12/3/)
    -   [CCSS.ELA-Literacy.RST.11-12.4](http://www.corestandards.org/ELA-Literacy/RST/11-12/4/)
    -   AP I.D.1
    -   AP I.D.2
    -   AP I.D.3
    -   AP I.D.4
    -   AP I.D.5
    -   AP IV.A.8
    -   AP IV.B.6
    -   AP IV.B.7

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

-   **Web Media: Annenberg Learner: “Correlation”**
    Link: Annenberg Learner:
    [“Correlation”](http://www.learner.org/resources/series65.html) (Flash)  
        
     Instructions: Choose Video 9, “Correlation,” by clicking on the VoD
    button to the right of the title. You will learn to derive and
    interpret the correlation coefficient using the relationship between
    a baseball player’s salary and his home run statistics. Then you
    will discover how to use the coefficient of determination to measure
    the strength and direction of a relationship between two variables.
    A study comparing sets of identical twins raised together and apart
    illustrates the concept of correlation.  
        
     Watching this lecture should take approximately 30 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-ID.C.8](http://www.corestandards.org/Math/Content/HSS/ID/C/8)
    -   [CCSS.Math.Content.HSS-ID.C.9](http://www.corestandards.org/Math/Content/HSS/ID/C/9)
    -   AP I.D.2

    Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above. 

-   **Web Media: SOPHIA: Ryan Backman’s “Correlation”**
    Link: SOPHIA: Ryan
    Backman’s [“Correlation”](http://www.sophia.org/correlation--2/correlation--7-tutorial) (HTML5)  
        
     Instructions: Watch the video. Work with Mr. Backman as he
    calculates a correlation coefficient for the relationship between
    the number of miles to work and the commute time.  
        
     Watching this video should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-ID.B.6](http://www.corestandards.org/Math/Content/HSS/ID/B/6)
    -   [CCSS.Math.Content.HSS-ID.C.8](http://www.corestandards.org/Math/Content/HSS/ID/C/8)
    -   [CCSS.Math.Content.HSS-ID.C.9](http://www.corestandards.org/Math/Content/HSS/ID/C/9)
    -   AP I.D.1
    -   AP I.D.2

    Terms of Use: This resource is licensed under a [Creative
    Commons Attribution-NonCommercial 3.0
    Unported](http://creativecommons.org/licenses/by-nc/3.0/).

-   **Web Media: SOPHIA: Ryan Backman’s “Positive and Negative
    Correlations”**
    Link: SOPHIA: Ryan Backman’s [“Positive and Negative
    Correlations”](http://www.sophia.org/positive-and-negative-correlations/positive-and-negative-correlations-tutorial) (HTML5)  
        
     Instructions: Watch the video. Make sure that you can identify
    whether the association is negative or positive and whether a given
    association is strong, moderate, or weak.  
        
     Watching this video should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-ID.B.6](http://www.corestandards.org/Math/Content/HSS/ID/B/6)
    -   [CCSS.Math.Content.HSS-ID.C.8](http://www.corestandards.org/Math/Content/HSS/ID/C/8)
    -   [CCSS.Math.Content.HSS-ID.C.9](http://www.corestandards.org/Math/Content/HSS/ID/C/9)
    -   AP I.D.1
    -   AP I.D.2

    Terms of Use: This resource is licensed under a [Creative
    Commons Attribution-NonCommercial 3.0
    Unported](http://creativecommons.org/licenses/by-nc/3.0/)<span
    style="line-height: 19.1875px;">.</span>

-   **Did I Get This? Activity: Stat Istics: “Guessing Correlations”**
    Link: Stat Istics: [“Guessing
    Correlations”](http://istics.net/stat/correlations/) (Java)  
        
     Instructions: Use the applet to guess the strength of the linear
    relationship (correlation) for a variety of scatterplots.  
        
     Completing this activity should take approximately 15 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   AP I.D.2

    Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above. 

-   **Did I Get This? Activity: OnlineStatBook: “Regression by Eye”**
    Link: OnlineStatBook: [“Regression by
    Eye”](http://www.onlinestatbook.com/stat_sim/reg_by_eye/index.html) (Java)  
        
     Instructions: For each scatterplot presented, you can use your
    mouse to draw the line that you think best fits the data. You may
    make several guesses and then check mark the “Draw the regression
    line” box and the true line of best fit will be displayed. On the
    right side of the applet box, you can guess the correlation from
    four choices. Check your answer by pressing on the “Show r” button.
    You can view as many scatterplots as you wish. For a new display,
    press the “New Data” button.  
        
     This activity allows you to get an intuitive sense of the value of
    the correlation coefficient, and it also gives you an introduction
    to the least-squares regression line, which will be fully introduced
    in the next subunit.  
        
     Completing this activity should take approximately 15 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-ID.B.6c](http://www.corestandards.org/Math/Content/HSS/ID/B/6/c)
    -   AP I.D.2

    Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above. 

-   **Web Media: SOPHIA: Ryan Backman’s “Correlation and Causation”**
    Link: SOPHIA: Ryan Backman’s [“Correlation and
    Causation”](http://www.sophia.org/correlation-and-causation/correlation-and-causation-tutorial) (HTML5)  
        
     Instructions: Watch the video. After watching this short video, you
    will better understand the famous phrase “Correlation does not
    necessarily imply causation.”  
        
     Watching this video should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-ID.B.6](http://www.corestandards.org/Math/Content/HSS/ID/B/6)
    -   [CCSS.Math.Content.HSS-ID.C.9](http://www.corestandards.org/Math/Content/HSS/ID/C/9)
    -   AP I.D.2

    Terms of Use: This resource is licensed under a [Creative
    Commons Attribution-NonCommercial 3.0
    Unported](http://creativecommons.org/licenses/by-nc/3.0/)<span
    style="line-height: 19.1875px;">.</span>

-   **Web Media: Khan Academy’s “Correlation and Causality”**
    Link: Khan Academy’s [“Correlation and
    Causality”](https://www.khanacademy.org/math/probability/regression/regression-correlation/v/correlation-and-causality) (YouTube)  
        
     Instructions: Watch the video. Using an article from the
    highly-esteemed website, WebMD.com, you will learn a practical
    lesson about the difference between correlation and causation.  
        
     Watching this lecture should take approximately 15 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-ID.B.6](http://www.corestandards.org/Math/Content/HSS/ID/B/6)
    -   AP I.D.2 

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Checkpoint: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 9.1: Scatterplots
    and Linear Correlation”; partially adapted from David Lane’s *Online
    Statistics Education: A Multimedia Course of Study* and CK-12:
    *Advanced Probability and Statistics***
    Link: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: [“Section 9.1: Scatterplots
    and Linear
    Correlation”](http://www.saylor.org/site/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Work on the review questions at the end of Section
    9.1. Note that you are to use the raw score formula for one of the
    calculations of the correlation coefficient. Make a series of
    columns for *X*, *Y*, *X*<sup>2</sup>, *Y*<sup>2</sup>, and *XY*, as
    was shown in the text. The calculation will be much easier to
    compute by using this method. A short answer key is provided at the
    end of the problem set. For a detailed solution, [click
    here](http://www.saylor.org/site/wp-content/uploads/2013/07/K12MATHAPSTATS-Flexbook-Answers-Sec-9.1-FINAL.pdf).  
        
     Completing the review questions should take approximately 1 hour.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-ID.B.6](http://www.corestandards.org/Math/Content/HSS/ID/B/6)
    -   [CCSS.Math.Content.HSS-ID.B.6a](http://www.corestandards.org/Math/Content/HSS/ID/B/6/a)
    -   [CCSS.Math.Content.HSS-ID.B.6b](http://www.corestandards.org/Math/Content/HSS/ID/B/6/b)
    -   [CCSS.Math.Content.HSS-ID.B.6c](http://www.corestandards.org/Math/Content/HSS/ID/B/6/c)
    -   [CCSS.Math.Content.HSS-ID.C.7](http://www.corestandards.org/Math/Content/HSS/ID/C/7)
    -   [CCSS.Math.Content.HSS-ID.C.8](http://www.corestandards.org/Math/Content/HSS/ID/C/8)
    -   [CCSS.Math.Content.HSS-ID.C.9](http://www.corestandards.org/Math/Content/HSS/ID/C/9)
    -   [CCSS.ELA-Literacy.RST.11-12.2](http://www.corestandards.org/ELA-Literacy/RST/11-12/2/)
    -   [CCSS.ELA-Literacy.RST.11-12.3](http://www.corestandards.org/ELA-Literacy/RST/11-12/3/)
    -   [CCSS.ELA-Literacy.RST.11-12.4](http://www.corestandards.org/ELA-Literacy/RST/11-12/4/)
    -   AP I.D.1
    -   AP I.D.2
    -   AP I.D.3
    -   AP I.D.4
    -   AP I.D.5
    -   AP IV.A.8
    -   AP IV.B.6
    -   AP IV.B.7

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

**9.2 Least-Squares Regression** <span id="9.2"></span> 
*The correlation coefficient tells us the strength of the linear
relationship between the explanatory and response variables, but we have
yet to determine which line we’re talking about. In this subunit, we
will study the “best” line for our data, using a technique called
least-squares regression. We will review the equation of a line and then
learn how it is used for predicting the value of a response variable
when we choose a particular value for the explanatory variable.*

-   **Explanation: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 9.2: Least-Squares
    Regression”; partially adapted from David Lane’s *Online Statistics
    Education: A Multimedia Course of Study* and CK-12: *Advanced
    Probability and Statistics***
    Link:The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s *Advanced
    Probability and Statistics*: [“Section 9.2: Least-Squares
    Regression”](http://www.saylor.org/site/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Read Section 9.2. The text presents calculations of
    the least-squares regression line with several formulas. While these
    are conceptually important, they are quite time consuming and
    impractical to use for real-world data. Your calculator use will
    make quick work of the cumbersome calculations and allow you to
    concentrate on the interpretation and analysis of the data.  
        
     Reading this section and taking notes should take approximately 1
    hour and 30 minutes.  
      
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-ID.B.6](http://www.corestandards.org/Math/Content/HSS/ID/B/6)
    -   [CCSS.Math.Content.HSS-ID.B.6a](http://www.corestandards.org/Math/Content/HSS/ID/B/6/a)
    -   [CCSS.Math.Content.HSS-ID.B.6b](http://www.corestandards.org/Math/Content/HSS/ID/B/6/b)
    -   [CCSS.Math.Content.HSS-ID.B.6c](http://www.corestandards.org/Math/Content/HSS/ID/B/6/c)
    -   [CCSS.Math.Content.HSS-ID.C.7](http://www.corestandards.org/Math/Content/HSS/ID/C/7)
    -   [CCSS.ELA-Literacy.RST.11-12.1](http://www.corestandards.org/ELA-Literacy/RST/11-12/1/)
    -   AP I.D.3
    -   AP I.D.4
    -   AP I.D.5

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

-   **Web Media: YouTube: Barbara Illowsky and Susan Dean’s “Linear
    Regression and Correlation”**
    Link: YouTube: Barbara Illowsky and Susan Dean’s [“Linear Regression
    and
    Correlation”](http://www.youtube.com/watch?v=Nugy6bOTEms&list=PL969D1B417D092FF2&index=6) (YouTube)  
        
     Instructions: Watch the video. Stop it at 15:30. The presenter
    gives an excellent review of scatterplots and introduces you to the
    least-squares regression line. Make note of the interpretation of a
    scatterplot when the slope of the line is 0. Know the definition of
    an outlier. When she discusses the prediction of the height of a
    70-year-old man, using the data from the age-height example, know
    that the term for this inappropriate activity is *extrapolation*,
    which is always dangerous.  
        
     Watching this lecture should take approximately 15 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-ID.B.6](http://www.corestandards.org/Math/Content/HSS/ID/B/6)
    -   [CCSS.Math.Content.HSS-ID.B.6a](http://www.corestandards.org/Math/Content/HSS/ID/B/6/a)
    -   [CCSS.Math.Content.HSS-ID.B.6b](http://www.corestandards.org/Math/Content/HSS/ID/B/6/b)
    -   [CCSS.Math.Content.HSS-ID.B.6c](http://www.corestandards.org/Math/Content/HSS/ID/B/6/c)
    -   [CCSS.Math.Content.HSS-ID.C.7](http://www.corestandards.org/Math/Content/HSS/ID/C/7)
    -   AP I.D.3
    -   AP I.D.4
    -   AP I.D.5

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution 2.0 Generic
    License](http://creativecommons.org/licenses/by/2.0/). It is
    attributed to Barbara Illowsky and Susan Dean and the original
    version can be found [here](http://cnx.org/content/m17572/latest/).

-   **Web Media: SOPHIA: Ryan Backman’s “Best-Fit Line and Regression
    Line”**
    Link: SOPHIA: Ryan Backman’s [“Best-Fit Line and Regression
    Line”](http://www.sophia.org/best-fit-line-and-regression-line/best-fit-line-and-regression-line-tutorial) (HTML5)  
        
     Instructions: Watch the video. The presenter shows the transition
    from scatterplot to least-squares regression, and he ties these two
    ideas together by showing both graphical displays and statistical
    calculations.  
        
     Watching this video should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-ID.B.6](http://www.corestandards.org/Math/Content/HSS/ID/B/6)
    -   [CCSS.Math.Content.HSS-ID.B.6a](http://www.corestandards.org/Math/Content/HSS/ID/B/6/a)
    -   [CCSS.Math.Content.HSS-ID.B.6c](http://www.corestandards.org/Math/Content/HSS/ID/B/6/c)
    -   AP I.D.3

    Terms of Use: This resource is licensed under a [Creative
    Commons Attribution-NonCommercial 3.0
    Unported](http://creativecommons.org/licenses/by-nc/3.0/).

-   **Web Media: SOPHIA: Ryan Backman’s “Interpreting Intercept and
    Slope”**
    Link: SOPHIA: Ryan Backman’s [“Interpreting Intercept and
    Slope”](http://www.sophia.org/interpreting-intercept-and-slope/interpreting-intercept-and-slope-tutorial) (HTML5)  
        
     Instructions: Watch the video. Please note that the regression
    equation from our text, which is given as ŷ = a + bx, is identical
    to the one used in the video by Mr. Backman, but he uses different
    letters for the *y*-intercept and the slope: ŷ = b<sub>0</sub> +
    b<sub>1</sub>x.  
        
     Watching this video should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-ID.C.7](http://www.corestandards.org/Math/Content/HSS/ID/C/7)
    -   AP I.D.3

    Terms of Use: This resource is licensed under a [Creative
    Commons Attribution-NonCommercial 3.0
    Unported](http://creativecommons.org/licenses/by-nc/3.0/).

-   **Web Media: SOPHIA: Ryan Backman’s “Predictions from Best-Fit
    Lines”**
    Link: SOPHIA: Ryan Backman’s [“Predictions from Best-Fit
    Lines”](http://www.sophia.org/predictions-from-best-fit-lines/predictions-from-best-fit-lines-tutorial) (HTML5)  
        
     Instructions: Watch the video. You will learn how to calculate a
    predicted value of the response variable using the regression
    equation. Then the presenter will caution you about the potential
    dangers of extrapolation.  
        
     Watching this video should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-ID.B.6a](http://www.corestandards.org/Math/Content/HSS/ID/B/6/a)
    -   [CCSS.Math.Content.HSS-ID.C.7](http://www.corestandards.org/Math/Content/HSS/ID/C/7)
    -   AP I.D.3

    Terms of Use: This resource is licensed under a [Creative
    Commons Attribution-NonCommercial 3.0
    Unported](http://creativecommons.org/licenses/by-nc/3.0/).

-   **Web Media: SOPHIA: Ryan Backman’s “Residuals”**
    Link: SOPHIA: Ryan Backman’s
    [“Residuals”](http://www.sophia.org/residuals/residuals-tutorial) (HTML5)  
        
     Instructions: Watch the video. The presenter reviews the basics of
    using the regression equation for prediction, and then he introduces
    you to calculation and display of residuals. This video augments the
    text, so pay close attention to residual plots and assessment of
    linearity.  
        
     Watching this video should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-ID.B.6b](http://www.corestandards.org/Math/Content/HSS/ID/B/6/b)
    -   AP I.D.4

    Terms of Use: This resource is licensed under a [Creative
    Commons Attribution-NonCommercial 3.0
    Unported](http://creativecommons.org/licenses/by-nc/3.0/).

-   **Web Media: SOPHIA: Jonathan Osters’ “Residuals”**
    Link: SOPHIA: Jonathan
    Osters’ [“Residuals”](http://www.sophia.org/residuals/residuals--2-tutorial) (HTML5)  
        
     Instructions: Watch the video. The presenter solidifies the concept
    of residuals, residual plots, and the use of the residual plot to
    indicate if a linear model is appropriate for the data.  
        
     Watching this video should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-ID.B.6b](http://www.corestandards.org/Math/Content/HSS/ID/B/6/b)
    -   AP I.D.4

    Terms of Use: This resource is licensed under a [Creative
    Commons Attribution-NonCommercial 3.0
    Unported](http://creativecommons.org/licenses/by-nc/3.0/).

-   **Checkpoint: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 9.2: Least-Squares
    Regression”; partially adapted from David Lane’s *Online Statistics
    Education: A Multimedia Course of Study* and CK-12: *Advanced
    Probability and Statistics***
    Link: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: [“Section 9.2: Least-Squares
    Regression”](http://www.saylor.org/site/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Work on the review questions at the end of Section
    9.2. You have one comprehensive question requiring you tie together
    all of the concepts presented in Section 9.1 and Section 9.2, from
    sketching a simple scatterplot to determining the least-squares
    regression line and plotting and analyzing the residuals. Use
    technology to assist you in your computations. There is no short
    answer key in the text. For a detailed solution, [click
    here](http://www.saylor.org/site/wp-content/uploads/2013/07/K12MATHAPSTATS-FlexBook-Answers-Sec-9.2-FINAL.pdf).  
        
     Completing the review questions should take approximately 1 hour
    and 30 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-ID.B.6](http://www.corestandards.org/Math/Content/HSS/ID/B/6)
    -   [CCSS.Math.Content.HSS-ID.B.6a](http://www.corestandards.org/Math/Content/HSS/ID/B/6/a)
    -   [CCSS.Math.Content.HSS-ID.B.6b](http://www.corestandards.org/Math/Content/HSS/ID/B/6/b)
    -   [CCSS.Math.Content.HSS-ID.B.6c](http://www.corestandards.org/Math/Content/HSS/ID/B/6/c)
    -   [CCSS.Math.Content.HSS-ID.C.7](http://www.corestandards.org/Math/Content/HSS/ID/C/7)
    -   [CCSS.ELA-Literacy.RST.11-12.1](http://www.corestandards.org/ELA-Literacy/RST/11-12/1/)
    -   AP I.D.3
    -   AP I.D.4
    -   AP I.D.5

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

**9.3 Inferences about Regression** <span id="9.3"></span> 
*We finish our study of linear regression with hypothesis testing. We
have learned how to calculate and interpret the slope of the regression
line, but now we will perform a hypothesis test to determine if it is
truly useful in prediction. *

-   **Explanation: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 9.3: Inferences
    about Regression”; partially adapted from David Lane’s *Online
    Statistics Education: A Multimedia Course of Study* and CK-12:
    *Advanced Probability and Statistics***
    Link:The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s *Advanced
    Probability and Statistics*: [“Section 9.3: Inferences about
    Regression”](http://www.saylor.org/site/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Read Section 9.3. We know how to draw a scatterplot,
    determine the least-squares prediction line, and interpret residual
    plots. In this section, we test the hypothesis about the slope of
    the regression line to ensure that we can trust that the predictions
    we make reflect a significant linear relationship between the
    explanatory and response variables.  
        
     Reading this section should take approximately 30 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   AP IV.A.8
    -   AP IV.B.7

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

-   **Web Media: Annenberg Learner: “Inference for Relationships”**
    Link: Annenberg Learner: [“Inference for
    Relationships”](http://www.learner.org/resources/series65.html) (Flash)  
        
     Instructions: Choose Video 25, “Inference for Relationships,” by
    clicking on the VoD button to the right of the title, and watch the
    video. In the video, you will follow the development of a famous
    puzzle in astronomy that was solved by astronomer Edwin Hubble, who
    studied the linear relationship between the distance of galaxies
    from the earth and their speed. The material presented after time
    19:30 is optional.  
        
     Watching this lecture should take approximately 30 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   AP IV.A.8
    -   AP IV.B.7

    Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above. 

-   **Checkpoint: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 9.3: Inferences
    about Regression”; partially adapted from David Lane’s *Online
    Statistics Education: A Multimedia Course of Study* and CK-12:
    *Advanced Probability and Statistics***
    Link: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: [“Section 9.3: Inferences
    about
    Regression”](http://www.saylor.org/site/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Work on the review questions at the end of Section
    9.3. A short answer key is provided at the end of the problem set.
    For a detailed solution, [click
    here](http://www.saylor.org/site/wp-content/uploads/2013/07/K12MATHAPSTATS-Unit-9-FlexBook-Answers-Sec-9.3-FINAL.pdf).  
        
     Completing the review questions should take approximately 1 hour
    and 30 minutes.  
      
     Standards Addressed (*Common Core and AP*):  

    -   AP IV.A.8
    -   AP IV.B.7

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

**Unit 9: Assessment** <span id="9.4"></span> 
-   **Assessment: The Saylor Foundation’s “Unit 9 Assessment”**
    Link: The Saylor Foundation’s [“Unit 9
    Assessment”](http://school.saylor.org/mod/quiz/view.php?id=1546) (HTML)  
      
     Instructions: Each multiple-choice question has five answer
    choices. You are to choose the answer choice that best answers the
    question. You may use your calculator and your formula sheet for all
    questions on this unit assessment.  
      
     You must be logged into your Saylor Foundation School account in
    order to access this exam. If you do not yet have an account, you
    should be able to create one, free of charge, after clicking on the
    link above.  
      
     Completing this assessment should take approximately 1 hour.  
      
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-ID.B.6](http://www.corestandards.org/Math/Content/HSS/ID/B/6)
    -   [CCSS.Math.Content.HSS-ID.B.6a](http://www.corestandards.org/Math/Content/HSS/ID/B/6/a)
    -   [CCSS.Math.Content.HSS-ID.B.6b](http://www.corestandards.org/Math/Content/HSS/ID/B/6/b)
    -   [CCSS.Math.Content.HSS-ID.B.6c](http://www.corestandards.org/Math/Content/HSS/ID/B/6/c)
    -   [CCSS.Math.Content.HSS-ID.C.7](http://www.corestandards.org/Math/Content/HSS/ID/C/7)
    -   [CCSS.Math.Content.HSS-ID.C.8](http://www.corestandards.org/Math/Content/HSS/ID/C/8)
    -   [CCSS.Math.Content.HSS-ID.C.9](http://www.corestandards.org/Math/Content/HSS/ID/C/9)
    -   [CCSS.ELA-Literacy.RST.11-12.2](http://www.corestandards.org/ELA-Literacy/RST/11-12/2/)
    -   [CCSS.ELA-Literacy.RST.11-12.3](http://www.corestandards.org/ELA-Literacy/RST/11-12/3/)
    -   [CCSS.ELA-Literacy.RST.11-12.4](http://www.corestandards.org/ELA-Literacy/RST/11-12/4/)
    -   AP I.D.1
    -   AP I.D.2
    -   AP I.D.3
    -   AP I.D.4
    -   AP I.D.5
    -   AP IV.A.8
    -   AP IV.B.6
    -   AP IV.B.7


