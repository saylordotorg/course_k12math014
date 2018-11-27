---
layout: default
title: "K12MATH014: Advanced Statistics"
course_description: "This course covers statistical calculations and graphical representations of data, probability, random variables and binomial distribution, the bell curve, statistical experimentation, data analysis, linear regression, and chi-square analysis."
next: ../Unit09
previous: ../Unit07
---
**Unit 8: Hypothesis Testing** <span id="8"></span> 
*A student competing in the science fair performs an experiment on the
growth of tomato plants. She applies fertilizer to one group of tomato
plants and no fertilizer to another group. At the end of the experiment,
she weighs all of the tomatoes grown in each group. The fertilizer group
averages 5.2 pounds per tomato plant, and the nonfertilizer group
averages 4.9 pounds per tomato plant.*  
    
 *It is obvious that the fertilizer group has produced a higher mean
yield, but is it just slightly higher or significantly higher? Could the
difference in the two yields be attributed to just chance, or did the
use of the fertilizer make a real difference? Could the fertilizer
company use these results to claim that their fertilizer will definitely
contribute to a higher plant yield?*  
    
 *This is an example of the type of experimental situation that you will
encounter in analyzing data and using the results to make an inference
about an entire population.*  
    
 *In previous units you learned about probability, sampling,
experimental design, and various statistical distributions. In Unit 8,
you will put all of this information together. You will perform actual
statistical tests of hypotheses and make decisions based on the
experimental outcomes. You will be using the same analysis techniques
and tools that professional researchers use on a daily basis. This unit
is the culmination of all previous units, and its mastery will stand you
in good stead for research you might conduct in the future.*

**Unit 8 Time Advisory**  
Completing this unit should take approximately 13 hours and 45
minutes.  
  
 ☐    Subunit 8.1: 2 hours and 30 minutes  
  
 ☐    Subunit 8.2: 1 hour and 30 minutes  
  
 ☐    Subunit 8.3: 1 hour and 15 minutes  
  
 ☐    Subunit 8.4: 2 hours and 55 minutes  
  
 ☐    Subunit 8.5: 4 hours and 35 minutes  
  
 ☐    Unit 8 Assessment: 1 hour

**Unit8 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:
-   List the steps of hypothesis testing.
-   Calculate and interpret type I and type II errors.
-   Perform hypothesis tests for large sample means, small sample means,
    matched pairs, two sample means, and one-sample and two-sample
    proportions. 

Standards Addressed (*Common Core and Advanced Placement*):
-   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)  
      
-   [CCSS.Math.Content.HSS-IC.A.2](http://www.corestandards.org/Math/Content/HSS/IC/A/2)  
      
-   [CCSS.Math.Content.HSS-IC.B.5](http://www.corestandards.org/Math/Content/HSS/IC/B/5)  
      
-   [CCSS.Math.Content.HSS-IC.B.6](http://www.corestandards.org/Math/Content/HSS/IC/B/6)  
      
-   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)  
      
-   [CCSS.ELA-Literacy.RST.11-12.3](http://www.corestandards.org/ELA-Literacy/RST/11-12/3/)  
      
-   [CCSS.ELA-Literacy.RST.11-12.8](http://www.corestandards.org/ELA-Literacy/RST/11-12/8/)  
      
-   AP III.D.4  
      
-   AP III.D.5  
      
-   AP III.D.7  
      
-   AP IV.A.6  
      
-   AP IV.B.1  
      
-   AP IV.B.2  
      
-   AP IV.B.3  
      
-   AP IV.B.4  
      
-   AP IV.B.5

**8.1 Hypothesis Testing and the *p*-Value** <span id="8.1"></span> 
*We are introduced to the concept and steps of formal hypothesis testing
in this section. Commit these steps to memory, because they will be used
throughout the rest of the course. There are two basic approaches to
hypothesis testing: The first is by use of critical values, where we
predefine the experimental outcomes that are so unusual they would lead
us to reject the null hypothesis. The second approach is called the
p-value approach, whereby we look at our experimental outcome and
calculate how unusual an outcome it is; if it is considered highly
unusual, then we reject the null hypothesis. You should be able to use
either approach.*

-   **Explanation: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 8.1: Hypothesis
    Testing and the P-Value”; partially adapted from David Lane’s
    *Online Statistics Education: A Multimedia Course of Study* and
    CK-12: *Advanced Probability and Statistics***
    Link:The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s *Advanced
    Probability and Statistics*: [“Section 8.1: Hypothesis Testing and
    the
    P-Value”](https://resources.saylor.org/archived/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Read Section 8.1. There are three distinct topics to
    this reading: the hypothesis testing procedure, calculation of the
    *p* value, and type I and type II errors. Make sure you are
    comfortable with each topic before proceeding to the next one. You
    should work each example problem with pencil, paper, and
    calculator.  
        
     Reading this section and taking notes should take approximately 1
    hour and 30 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)
    -   [CCSS.ELA-Literacy.RST.11-12.3](http://www.corestandards.org/ELA-Literacy/RST/11-12/3/)
    -   [CCSS.ELA-Literacy.RST.11-12.8](http://www.corestandards.org/ELA-Literacy/RST/11-12/8/)
    -   AP IV.B.1
    -   AP IV.B.4

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

-   **Web Media: Khan Academy’s “Hypothesis Testing and *P*-Values”**
    Link: Khan Academy’s [“Hypothesis Testing and
    *P*-Values”](https://www.khanacademy.org/math/probability/statistics-inferential/hypothesis-testing/v/hypothesis-testing-and-p-values) (YouTube)  
        
     Instructions: Watch the video for an example of the basics of
    hypothesis testing.  
        
     Watching this lecture should take approximately 15 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)
    -   AP IV.B.1

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Web Media: Khan Academy’s “One-Tailed and Two-Tailed Tests”**
    Link: Khan Academy’s [“One-Tailed and Two-Tailed
    Tests”](https://www.khanacademy.org/math/probability/statistics-inferential/hypothesis-testing/v/one-tailed-and-two-tailed-tests) (YouTube)  
        
     Instructions: Watch the video. The presenter continues the previous
    video but introduces the one-tailed test and compares it to a
    two-tailed test.  
        
     Watching this lecture should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   AP IV.B.1

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Web Media: Khan Academy’s “Type 1 Errors”**
    Link: Khan Academy’s [“Type 1
    Errors”](https://www.khanacademy.org/math/probability/statistics-inferential/hypothesis-testing/v/type-1-errors) (YouTube)  
        
     Instructions: Watch the video. It is possible to perform a
    hypothesis test correctly but to still make a statistical error.
    Making a type 1 error is rejecting the null hypothesis when it is
    true.  
        
     Watching this lecture should take approximately 5 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   AP IV.B.1

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Checkpoint: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 8.1: Hypothesis
    Testing and the P-Value”; partially adapted from David Lane’s
    *Online Statistics Education: A Multimedia Course of Study* and
    CK-12: *Advanced Probability and Statistics***
    Link: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: [“Section 8.1: Hypothesis
    Testing and the
    P-Value”](https://resources.saylor.org/archived/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Work on the review questions at the end of Section
    8.1. Most of the questions are concept questions rather than
    calculation problems.  A short answer key is provided at the end of
    the problem set. For a detailed solution, [click
    here](https://resources.saylor.org/archived/wp-content/uploads/2013/07/K12MATHAPSTATS-Unit-8-FlexBook-Answers-Sec-8.1-FINAL.pdf).  
        
     Completing the review questions should take approximately 30
    minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)
    -   [CCSS.ELA-Literacy.RST.11-12.3](http://www.corestandards.org/ELA-Literacy/RST/11-12/3/)
    -   [CCSS.ELA-Literacy.RST.11-12.8](http://www.corestandards.org/ELA-Literacy/RST/11-12/8/)
    -   AP IV.B.1
    -   AP IV.B.4 

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

**8.2 Testing a Proportion Hypothesis** <span id="8.2"></span> 
*Thus far, we have seen hypothesis testing about means. In this section,
we are introduced to testing hypotheses about proportions. The same
concepts apply, and we still use the six steps of hypothesis testing,
and we still calculate p-values. The only difference is that we use
different calculation formulas for the standard error and for the test
statistic.*

-   **Explanation: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 8.2: Testing a
    Proportion Hypothesis”; partially adapted from David Lane’s *Online
    Statistics Education: A Multimedia Course of Study* and CK-12:
    *Advanced Probability and Statistics***
    Link:The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s *Advanced
    Probability and Statistics*: [“Section 8.2: Testing a Proportion
    Hypothesis”](https://resources.saylor.org/archived/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Read Section 8.2. The steps used for testing a
    hypothesis in the previous subunit are the same here, except now you
    are testing a population proportion rather than a population mean.  
        
     Reading this section should take approximately 45 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.A.2](http://www.corestandards.org/Math/Content/HSS/IC/A/2)
    -   [CCSS.Math.Content.HSS-IC.B.6](http://www.corestandards.org/Math/Content/HSS/IC/B/6)
    -   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)
    -   AP III.D.4
    -   AP III.D.5
    -   AP III.D.7
    -   AP IV.B.1
    -   AP IV.B.2 

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

-   **Web Media: Khan Academy’s “Large Sample Proportion Hypothesis
    Testing”**
    Link: Khan Academy’s [“Large Sample Proportion Hypothesis
    Testing”](https://www.khanacademy.org/math/probability/statistics-inferential/hypothesis-testing/v/large-sample-proportion-hypothesis-testing) (YouTube)  
        
     Instructions: Watch the video for an example of hypothesis testing
    for a population proportion *p*.  
        
     Watching this lecture should take approximately 15 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP IV.B.2

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Checkpoint: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 8.2: Testing a
    Proportion Hypothesis”; partially adapted from David Lane’s *Online
    Statistics Education: A Multimedia Course of Study* and CK-12:
    *Advanced Probability and Statistics***
    Link: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: [“Section 8.2: Testing a
    Proportion
    Hypothesis”](https://resources.saylor.org/archived/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Work on the review questions at the end of Section
    8.2. For the hypothesis testing questions, use the six-step
    procedure, as shown in Section 8.2 of the text and previous video. 
    A short answer key is provided at the end of the problem set. For a
    detailed solution, [click
    here](https://resources.saylor.org/archived/wp-content/uploads/2013/07/K12MATHAPSTATS-Unit-8-FlexBook-Answers-Sec-8.2-FINAL-w-one-comment.pdf).  
        
     Completing the review questions should take approximately 30
    minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.A.2](http://www.corestandards.org/Math/Content/HSS/IC/A/2)
    -   [CCSS.Math.Content.HSS-IC.B.6](http://www.corestandards.org/Math/Content/HSS/IC/B/6)
    -   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)
    -   AP III.D.4
    -   AP III.D.5
    -   AP III.D.7
    -   AP IV.B.1
    -   AP IV.B.2

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

**8.3 Testing a Mean Hypothesis** <span id="8.3"></span> 
*This section formalizes the material covered in Section 8.1. Review the
hypothesis test steps, and do each problem in the end-of-section
checkpoint.*

-   **Explanation: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 8.3: Testing a Mean
    Hypothesis”; partially adapted from David Lane’s *Online Statistics
    Education: A Multimedia Course of Study* and CK-12: *Advanced
    Probability and Statistics***
    Link:The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s *Advanced
    Probability and Statistics*: [“Section 8.3: Testing a Mean
    Hypothesis”](https://resources.saylor.org/archived/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Read Section 8.3. This short section takes you
    through the process of a large-sample test for the mean. Follow the
    example step by step.  
        
     Reading this section should take approximately 20 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.A.2](http://www.corestandards.org/Math/Content/HSS/IC/A/2)
    -   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)
    -   AP IV.B.1
    -   AP IV.B.4 

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

-   **Explanation: SOPHIA: Ryan Backman's “*z*-Test for Population
    Means”**
    Link: SOPHIA: Ryan Backman's [“*z*-Test for Population
    Means”](http://www.sophia.org/z-test-for-population-means/z-test-for-population-means--4-tutorial) (HTML5)  
        
     Instructions: Watch the video for an example that takes you through
    a hypothesis test using the standard normal distribution.  
        
     Watching this lecture should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)
    -   AP IV.B.1
    -   AP IV.B.4 

    Terms of Use: This resource is licensed under a [Creative
    Commons Attribution-NonCommercial 3.0
    Unported](http://creativecommons.org/licenses/by-nc/3.0/).

-   **Checkpoint: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 8.3: Testing a Mean
    Hypothesis”; partially adapted from David Lane’s *Online Statistics
    Education: A Multimedia Course of Study* and CK-12: *Advanced
    Probability and Statistics***
    Link: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: [“Section 8.3: Testing a Mean
    Hypothesis”](https://resources.saylor.org/archived/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Work on the review questions at the end of Section
    8.3. Be sure to use the six-step procedure for a large sample test
    for a mean.  A short answer key is provided at the end of the
    problem set. For a detailed solution, [click
    here](https://resources.saylor.org/archived/wp-content/uploads/2013/07/K12MATHAPSTATS-Unit-8-FlexBook-Answers-Sec-8.3-FINAL.pdf).  
        
     Completing the review questions should take approximately 45
    minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.A.2](http://www.corestandards.org/Math/Content/HSS/IC/A/2)
    -   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)
    -   AP IV.B.1
    -   AP IV.B.4

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

**8.4 Student’s *t*-Distribution** <span id="8.4"></span> 
*Up to this point, we have performed hypothesis tests with the
z-distribution, which can be used for large sample means, defined as
having a sample size greater than 30. We can also use the z-distribution
for testing population proportions. In Section 8.4, we learn how to
treat small samples with the t-distribution. In addition to reading the
text, make sure you also pay close attention to the videos and that you
can use a calculator when given raw data to analyze. You should know how
to use the small-sample t-distribution for both hypothesis testing and
confidence intervals.*

-   **Explanation: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 8.4: Student’s
    t-Distribution”; partially adapted from David Lane’s *Online
    Statistics Education: A Multimedia Course of Study* and CK-12:
    *Advanced Probability and Statistics***
    Link:The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s *Advanced
    Probability and Statistics*: [“Section 8.4: Student’s
    t-Distribution”](https://resources.saylor.org/archived/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Read Section 8.4. As you read, note the differences
    between the *z* distribution and the *t* distribution. Work the
    examples, first with pencil and paper and then using the calculator.
    Pay close attention to the calculation of the confidence interval
    for small samples.  
        
     Reading this section and taking notes should take approximately 1
    hour.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.A.2](http://www.corestandards.org/Math/Content/HSS/IC/A/2)
    -   [CCSS.Math.Content.HSS-IC.B.6](http://www.corestandards.org/Math/Content/HSS/IC/B/6)
    -   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)
    -   AP III.D.7
    -   AP IV.A.6
    -   AP IV.B.4

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

-   **Explanation: Wikipedia: “Table of Selected Values (of the t
    Distribution)”**
    Link: Wikipedia: [“Table of Selected Values (of the *t*
    Distribution)”](https://resources.saylor.org/archived/wp-content/uploads/2013/07/Table-of-Selected-Values-of-the-t-Distribution.pdf) (PDF)  
        
     Instructions: Print the *t* table for future use or keep the link
    available for use when you are completing checkpoints or the final
    assessment.  
        
     Accessing and printing this table should take approximately 10
    minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   AP III.D.7

    Terms of Use: This resource is licensed under a [Creative Common
    Attribution-ShareAlike 3.0
    Unported](http://creativecommons.org/licenses/by-sa/3.0/). It is
    attributed to Wikipedia and the original version can be found
    [here](http://en.wikipedia.org/w/index.php?title=Student%27s_t-distribution&oldid=565142552).

-   **Web Media: Khan Academy’s “Z-Statistics vs. T-Statistics”**
    Link: Khan Academy’s [“Z-Statistics vs.
    T-Statistics”](https://www.khanacademy.org/math/probability/statistics-inferential/hypothesis-testing/v/z-statistics-vs--t-statistics) (YouTube)  
        
     Instructions: Watch the video (6:39). We move from the *z* test
    statistic to the *t* test statistic in this video. It is necessary
    to use the sample standard deviation *s* as the estimate for σ in
    many small-sample hypothesis tests.  
        
     Watching this lecture should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP III.D.7

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Web Media: Khan Academy’s “Small Sample Hypothesis Test”**
    Link: Khan Academy’s [“Small Sample Hypothesis
    Test”](https://www.khanacademy.org/math/probability/statistics-inferential/hypothesis-testing/v/small-sample-hypothesis-test) (YouTube)  
        
     Instructions: Watch the video. A sample problem with raw data is
    provided. It is necessary to use the sample standard deviation s as
    the estimate for σ in many small-sample hypothesis tests.  
        
     Watching this lecture should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP IV.B.4

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Web Media: SOPHIA: Ryan Backman’s “Confidence Intervals Using the
    T-Distribution”**
    Link: SOPHIA: Ryan Backman’s [“Confidence Intervals Using the
    T-Distribution”](http://www.sophia.org/confidence-intervals-using-the-t-distribution/confidence-intervals-using-the-t-distribution--4-tutorial) (HTML5)  
        
     Instructions: Watch the video. We previously learned how to
    calculate confidence intervals with the *z* distribution. Now we
    learn in this video how to use the confidence interval formula when
    use of a *t* distribution is indicated.  
        
     Watching this lecture should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP IV.A.6

    Terms of Use: This resource is licensed under a [Creative
    Commons Attribution-NonCommercial 3.0
    Unported](http://creativecommons.org/licenses/by-nc/3.0/)<span
    style="line-height: 19.1875px;">.</span>

-   **Web Media: Khan Academy’s “T-Statistic Confidence Interval”**
    Link: Khan Academy’s [“T-Statistic Confidence
    Interval”](https://www.khanacademy.org/math/probability/statistics-inferential/hypothesis-testing/v/t-statistic-confidence-interval) (YouTube)  
        
     Instructions: Watch the video. We previously learned how to
    calculate confidence intervals with the *z* distribution. Now we
    learn in this video how to use the confidence interval formula when
    use of a *t* distribution is indicated.  
        
     Watching this lecture should take approximately 15 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP IV.A.6

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Checkpoint: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 8.4: Student’s
    t-Distribution”; partially adapted from David Lane’s *Online
    Statistics Education: A Multimedia Course of Study* and CK-12:
    *Advanced Probability and Statistics***
    Link: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: [“Section 8.4: Student’s
    t-Distribution”](https://resources.saylor.org/archived/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Work on the review questions at the end of Section
    8.4. Solve the GPA problem using both the manual formula and the
    calculator. Use your calculator for the calculation of the
    confidence interval.  A short answer key is provided at the end of
    the problem set. For a detailed solution, [click
    here](https://resources.saylor.org/archived/wp-content/uploads/2013/07/K12MATHAPSTATS-Unit-8-FlexBook-Answers-Sec-8.4-FINAL.pdf).  
        
     Completing the review questions should take approximately 1 hour.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.A.2](http://www.corestandards.org/Math/Content/HSS/IC/A/2)
    -   [CCSS.Math.Content.HSS-IC.B.6](http://www.corestandards.org/Math/Content/HSS/IC/B/6)
    -   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)
    -   AP III.D.7
    -   AP IV.A.6
    -   AP IV.B.4

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

**8.5 Testing a Hypothesis for Dependent and Independent Samples** <span
id="8.5"></span> 
*In previous sections, we have tested hypotheses where we have taken a
single sample from a population and tested the statistic (the sample
mean or the sample proportion) against a particular value. In Section
8.5, we now consider two cases: 1) a matched-pair hypothesis test, where
**two** measurements are obtained from the same individual and the
difference is analyzed; or 2) two independent samples that are taken
from two different populations and the two calculated sample means or
proportions are compared to each other.*  
    
 *You will find the manual formulas overwhelming, but every procedure is
also supported by a calculator procedure. This will allow you to
concentrate on the concept rather than the computations.*

-   **Explanation: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 8.5: Testing a
    Hypothesis for Dependent and Independent Samples”; partially adapted
    from David Lane’s *Online Statistics Education: A Multimedia Course
    of Study* and CK-12: *Advanced Probability and Statistics***
    Link:The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s *Advanced
    Probability and Statistics*: [“Section 8.5: Testing a Hypothesis for
    Dependent and Independent
    Samples”](https://resources.saylor.org/archived/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
      
     Instructions: Read Section 8.5. Read carefully, and use paper and
    pencil to replicate the example problems. Use your calculator where
    indicated.  
      
     Reading this section and taking notes should take approximately 2
    hours.  
      
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.A.2](http://www.corestandards.org/Math/Content/HSS/IC/A/2)
    -   [CCSS.Math.Content.HSS-IC.B.5](http://www.corestandards.org/Math/Content/HSS/IC/B/5)
    -   [CCSS.Math.Content.HSS-IC.B.6](http://www.corestandards.org/Math/Content/HSS/IC/B/6)
    -   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)
    -   [CCSS.ELA-Literacy.RST.11-12.3](http://www.corestandards.org/ELA-Literacy/RST/11-12/3/)
    -   [CCSS.ELA-Literacy.RST.11-12.8](http://www.corestandards.org/ELA-Literacy/RST/11-12/8/)
    -   AP III.D.4
    -   AP III.D.5
    -   AP III.D.7
    -   AP IV.B.1
    -   AP IV.B.3
    -   AP IV.B.5 

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

-   **Web Media: YouTube: Barbara Illowsky and Susan Dean’s “Hypothesis
    Testing with Two Means”**
    Link: YouTube: Barbara Illowsky and Susan Dean’s [“Hypothesis
    Testing with Two
    Means”](http://www.youtube.com/watch?v=oW1QIUgl5fo) (YouTube)  
        
     Instructions: Watch the video. It provides an excellent
    introduction to testing hypotheses about two means (matched pairs or
    two independent samples) and two proportions. There is a lot of
    material in Section 8.5, and this video clarifies and supplements
    the text. The lecturer shows both the manual and the calculator
    techniques for conducting the various hypothesis tests in this
    section.  
        
     Watching this lecture should take approximately 30 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.B.5](http://www.corestandards.org/Math/Content/HSS/IC/B/5)
    -   AP IV.A.5
    -   AP IV.A.7

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution 2.0 Generic
    License](http://creativecommons.org/licenses/by/2.0/). It is
    attributed to Barbara Illowsky and Susan Dean and the original
    version can be found [here](http://cnx.org/content/m17577/latest/).

-   **Web Media: Khan Academy’s “Hypothesis Test for Difference of
    Means”**
    Link: Khan Academy’s [“Hypothesis Test for Difference of
    Means”](https://www.khanacademy.org/math/probability/statistics-inferential/hypothesis-testing-two-samples/v/hypothesis-test-for-difference-of-means) (YouTube)  
        
     Instructions: Watch the video. Work the problem along with the
    presenter.  
        
     Watching this lecture and working the problem should take
    approximately 15 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.B.5](http://www.corestandards.org/Math/Content/HSS/IC/B/5)
    -   AP IV.A.5
    -   AP IV.A.7

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Web Media: Khan Academy’s “Hypothesis Testing Comparing Population
    Proportions”**
    Link: Khan Academy’s [“Hypothesis Testing Comparing Population
    Proportions”](https://www.khanacademy.org/math/probability/statistics-inferential/hypothesis-testing-two-samples/v/hypothesis-test-comparing-population-proportions) (YouTube)  
        
     Instructions: Watch the video. The presenter performs a hypothesis
    test about two proportions. See if you can work the problem at the
    same time that he does.  
        
     Watching this lecture and working the problem should take
    approximately 20 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.B.5](http://www.corestandards.org/Math/Content/HSS/IC/B/5)
    -   AP IV.A.5
    -   AP IV.A.7

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Checkpoint: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 8.5: Testing a
    Hypothesis for Dependent and Independent Samples”; partially adapted
    from David Lane’s *Online Statistics Education: A Multimedia Course
    of Study* and CK-12: *Advanced Probability and Statistics***
    Link: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: [“Section 8.5: Testing a
    Hypothesis for Dependent and Independent
    Samples”](https://resources.saylor.org/archived/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
          
     Instructions: Work on the review questions at the end of Section
    8.5. The first approach for solving the problems is to note how many
    samples there are; then determine if the experiment or study is
    measuring matched pairs or two independent samples. Finally,
    determine what they are measuring: is it a paired difference, a
    difference of two means, or two proportions?  
        
     By making these three observations, you will know which procedure
    is appropriate for each question. There are hints in the problems
    themselves as to which procedure to use.  A short answer key is
    provided at the end of the problem set. For a detailed solution,
    [click
    here](https://resources.saylor.org/archived/wp-content/uploads/2013/07/K12MATHAPSTATS-Unit-8-FlexBook-Answers-Sec-8.5-FINAL.pdf).  
        
     Completing the review questions should take approximately 1 hour
    and 30 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.A.2](http://www.corestandards.org/Math/Content/HSS/IC/A/2)
    -   [CCSS.Math.Content.HSS-IC.B.5](http://www.corestandards.org/Math/Content/HSS/IC/B/5)
    -   [CCSS.Math.Content.HSS-IC.B.6](http://www.corestandards.org/Math/Content/HSS/IC/B/6)
    -   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)
    -   [CCSS.ELA-Literacy.RST.11-12.3](http://www.corestandards.org/ELA-Literacy/RST/11-12/3/)
    -   [CCSS.ELA-Literacy.RST.11-12.8](http://www.corestandards.org/ELA-Literacy/RST/11-12/8/)
    -   AP III.D.4
    -   AP III.D.5
    -   AP III.D.7
    -   AP IV.B.1
    -   AP IV.B.3
    -   AP IV.B.5

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

**Unit 8: Assessment** <span id="8.6"></span> 
-   **Assessment: The Saylor Foundation’s “Unit 8 Assessment”**
    Link: The Saylor Foundation’s [“Unit 8
    Assessment”](http://school.saylor.org/mod/quiz/view.php?id=1631) (HTML)  
        
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

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.A.2](http://www.corestandards.org/Math/Content/HSS/IC/A/2)
    -   [CCSS.Math.Content.HSS-IC.B.5](http://www.corestandards.org/Math/Content/HSS/IC/B/5)
    -   [CCSS.Math.Content.HSS-IC.B.6](http://www.corestandards.org/Math/Content/HSS/IC/B/6)
    -   [CCSS.Math.Content.HSS-MD.B.7](http://www.corestandards.org/Math/Content/HSS/MD/B/7)
    -   [CCSS.ELA-Literacy.RST.11-12.3](http://www.corestandards.org/ELA-Literacy/RST/11-12/3/)
    -   [CCSS.ELA-Literacy.RST.11-12.8](http://www.corestandards.org/ELA-Literacy/RST/11-12/8/)
    -   AP III.D.4
    -   AP III.D.5
    -   AP III.D.7
    -   AP IV.A.6
    -   AP IV.B.1
    -   AP IV.B.2
    -   AP IV.B.3
    -   AP IV.B.4
    -   AP IV.B.5


