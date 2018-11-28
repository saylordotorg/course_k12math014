---
layout: default
title: "K12MATH014: Advanced Statistics"
course_description: "This course covers statistical calculations and graphical representations of data, probability, random variables and binomial distribution, the bell curve, statistical experimentation, data analysis, linear regression, and chi-square analysis."
next: ../Unit08
previous: ../Unit06
---
**Unit 7: Sampling Distributions and Estimations** <span id="7"></span> 
*“Four out of five dentists surveyed recommend sugarless gum for their
patients who chew gum.”*  
    
 *This is a statement that has been part of a television commercial for
many years. Reread the statement. Does this mean that they asked just 5
dentists, and 4 of them recommended sugarless gum? Or did they ask 50
dentists, and 40 of them recommended sugarless gum? Or did they ask
50,000 dentists? Does it matter? Would you trust the statement more if
they had asked 50,000 dentists instead of 5?*  
    
 *In Unit 7, you will learn that it certainly does make a difference.
You will find out that if you have a representative sample, a large
sample size will yield more trustworthy results. This is the realm of
sampling distributions and confidence intervals. These unwieldy sounding
concepts provide basic tools for statisticians to use when they decide
how big a sample they need and how much “error” they can be comfortable
with.*  
    
 *Political pollsters use margins of error when they report approval
ratings for politicians (e.g., 42% approval rate, ± 3%) to give a
complete picture of opinion data that they have collected. You will
learn why these are important and how to calculate them yourself. *

**Unit 7 Time Advisory**  
Completing this unit should take approximately 11 hours and 20
minutes.  
  
 ☐    Subunit 7.1: 1 hour and 40 minutes  
  
 ☐    Subunit 7.2: 4 hours and 25 minutes  
  
 ☐    Subunit 7.3: 4 hours and 15 minutes  
  
 ☐    Unit 7 Assessment: 1 hour

**Unit7 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   Define the sampling distribution of the mean.  
      
-   Apply The Central Limit Theorem to a given data set.  
      
-   Calculate a point estimate for the mean and for the proportion.  
      
-   Construct and interpret a confidence interval for a population mean
    and for a population proportion. 

Standards Addressed (*Common Core and AP*):  
-   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)  
      
-   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)  
      
-   [CCSS.ELA-Literacy.RST.11-12.2](http://www.corestandards.org/ELA-Literacy/RST/11-12/2/)  
      
-   [CCSS.ELA-Literacy.RST.11-12.6](http://www.corestandards.org/ELA-Literacy/RST/11-12/6/)  
      
-   [CCSS.ELA-Literacy.RST.11-12.7](http://www.corestandards.org/ELA-Literacy/RST/11-12/7/)  
      
-   [CCSS.ELA-Literacy.RST.11-12.9](http://www.corestandards.org/ELA-Literacy/RST/11-12/9/)  
      
-   AP III.D.1  
      
-   AP III.D.2  
      
-   AP III.D.3  
      
-   AP III.D.6  
      
-   AP IV.A.1  
      
-   AP IV.A.2  
      
-   AP IV.A.3  
      
-   AP IV.A.4  
      
-   AP IV.A.6

**7.1 Introduction to Sampling Distributions** <span id="7.1"></span> 
*The concept of the sampling distribution is sometimes challenging. The
important thing to remember is that you are no longer using individual
pieces of raw data, but now you are studying the behavior of the sample
mean or the sample proportion. This first section is just an
introduction to a concept that will be studied in more depth in Section
7.2.*

-   **Explanation: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 7.1: Introduction to
    Sampling Distributions”; partially adapted from David Lane’s *Online
    Statistics Education: A Multimedia Course of Study* and CK-12:
    *Advanced Probability and Statistics***
    Link:The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s *Advanced
    Probability and Statistics*: [“Section 7.1: Introduction to Sampling
    Distributions”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Read Section 7.1. Pay close attention to the two
    displays of possible outcomes of the pool balls. Reread the section,
    making sure you can state the definition of the sampling
    distribution.  
        
     Reading this section should take approximately 30 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.ELA-Literacy.RST.11-12.6](http://www.corestandards.org/ELA-Literacy/RST/11-12/6/)
    -   AP III.D.1
    -   AP III.D.2

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

-   **Web Media: SOPHIA: Jonathan Oster’s “Distribution of Sample
    Proportions”**
    Link: SOPHIA: Jonathan Oster’s [“Distribution of Sample
    Proportions”](http://www.sophia.org/distribution-of-sample-proportions/distribution-of-sample-proportions--3-tutorial) (HTML)  
      
     Instructions: Watch the video. The text showed you the sampling
    distribution of the sample mean; this video extends the same idea of
    the sampling distribution but for the sample proportion. Note that
    in formulas, the presenter uses “*q*,” which is equal to (1 - *p*).
    Also note the presenter’s use of the term “standard error,” which
    was also used in the text and will be used extensively throughout
    the rest of the course.  
        
     Watching this video should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.ELA-Literacy.RST.11-12.9](http://www.corestandards.org/ELA-Literacy/RST/11-12/9/)
    -   AP III.D.1
    -   AP III.D.2

    Terms of Use: This resource is licensed under a [Creative
    Commons Attribution-NonCommercial 3.0
    Unported](http://creativecommons.org/licenses/by-nc/3.0/)<span
    style="line-height: 19.1875px;">.</span>

-   **Interactive Lab: Rossman and Chance’s “Reese’s Pieces Samples”**
    Link: Rossman and Chance’s [“Reese’s Pieces
    Samples”](http://statweb.calpoly.edu/chance/applets/Reeses/ReesesPieces.html) (Java)  
        
     Instructions: Use the applet to view the shape of the sampling
    distribution of sample proportions. This is an illustration of the
    sampling distribution of the sample proportion. At first, use a
    sample size of 10, and choose 50 samples. Notice that the symbol π
    stands for the true value of the population proportion. (Our text
    uses *p* instead of π.) The default setting for π is .5. Click on
    the “Draw Samples” button. After each sample of 10 pieces of candy
    falls from the machine, the sample proportion *p̂* will be displayed
    in red, just below the bin, and then its value will be graphed on
    the axes. After the 50 samples have been taken, look at the shape of
    the graph. Is it normal? Are the sample proportions close to the
    mean π or are they very far from it?  
        
     Repeat the experiment but now increase the sample size to 30. Keep
    the number of samples at 50. As each sample proportion is
    calculated, the dark black dots will overlay the gray dots from the
    previous exercise. Compare these two distributions. What is the mean
    of each? Which distribution is more tightly packed around the
    mean?  
        
     Now put a check mark in the box next to “Plot Normal Curve.” Which
    of the two distributions is closer to being a normal curve?  
        
     Continue with the applet by changing the value of π, the sample
    size, and the number of samples. You will find that as long as the
    sample size is large (greater than about 20 or so) and the number of
    samples is sufficient (about 40 or more), you will end up with a
    roughly normal distribution of the sample proportion.  
        
     Performing this applet exercise should take approximately 30
    minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP III.D.1

    Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above. 

-   **Checkpoint: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 7.1: Introduction to
    Sampling Distributions”; partially adapted from David Lane’s *Online
    Statistics Education: A Multimedia Course of Study* and CK-12:
    *Advanced Probability and Statistics***
    Link:The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s *Advanced
    Probability and Statistics*: [“Section 7.1: Introduction to Sampling
    Distributions”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Work on the 3 concept questions at the end of Section
    7.1. There are no numerical questions yet; they will come in later
    sections of Unit 7. For a detailed solution to the concept
    questions, [click
    here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2013/07/K12MATHAPSTATS-Unit-7-FlexBook-Answers-Sec.-7.1-FINAL.pdf).  
        
     Completing the concept questions should take approximately 30
    minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.ELA-Literacy.RST.11-12.6](http://www.corestandards.org/ELA-Literacy/RST/11-12/6/)
    -   AP III.D.1
    -   AP III.D.2

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

**7.2 The Central Limit Theorem** <span id="7.2"></span> 
*The Central Limit Theorem is one of the great theorems of mathematics
and statistics. It tells us that if we concentrate not on single data
values but rather on the mean of a sample of data values, the sample
mean will have a normal distribution, even if the original distribution
was nonnormal. It is critical for you to read the text carefully and
watch the videos with great attention. We will use The Central Limit
Theorem in nearly every section throughout the rest of the course.*

-   **Explanation: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 7.2: The Central
    Limit Theorem”; partially adapted from David Lane’s *Online
    Statistics Education: A Multimedia Course of Study* and CK-12:
    *Advanced Probability and Statistics***
    Link:The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s *Advanced
    Probability and Statistics*: [“Section 7.2: The Central Limit
    Theorem”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Read Section 7.2. Make note of the new notation for
    the mean and standard deviation of the sampling distribution of the
    mean and of the proportion. Work each example as given.  
        
     Reading this section and taking notes should take approximately 1
    hour.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP III.D.1
    -   AP III.D.2
    -   AP III.D.3
    -   AP III.D.6
    -   AP IV.A.1
    -   AP IV.A.2
    -   AP IV.A.3
    -   AP IV.A.4
    -   AP IV.A.6

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

-   **Web Media: YouTube: Barbara Illowsky and Susan Dean’s “The Central
    Limit Theorem”**
    Link: YouTube: Barbara Illowsky and Susan Dean’s [“The Central Limit
    Theorem”](http://www.youtube.com/watch?v=1IOEbMPKj8I) (YouTube)  
        
     Instructions: Watch the video. The presenter gives an excellent
    development of The Central Limit Theorem. This video is very easy to
    understand, as she guides you through the example with the means of
    the different number of dice that are thrown. She ends the example
    with a statement of The Central Limit Theorem.  
        
     In the dice role example, as the number of dice increased, what
    happened to the mean of each frequency distribution? Did the mean
    increase, decrease, or stay the same? What happened to the standard
    deviation? Did it increase, decrease, or stay the same?  
        
     The instructor graphed each distribution. What was the shape of the
    original distribution? Was it uniform or normal? How about the shape
    of the graphs of the means? Uniform or normal?  
        
     Make sure that you are very familiar with the new symbols
    introduced both in our text and in this video. They
    are *I<sub>x</sub>, I<sub>x̅</sub>, O<sub>x</sub>, and
    O<sub>x̅</sub>.* Be sure you can use each of these appropriately.  
        
     Finally, make sure that you work on the sample problem about
    baseball along with the instructor. Make sure you have either your
    calculator or your table of standard normal probabilities available
    when you watch the video. Stop the video if you need time to work on
    the problem and continue when you are finished.  
        
     Watching this lecture and working the sample problem should take
    approximately 40 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP III.D.2
    -   AP III.D.3

    Terms of Use: This work is licensed under a [Creative Commons
    Attribution 2.0 Generic
    License](http://creativecommons.org/licenses/by/2.0/). It is
    attributed to Barbara Illowsky and Susan Dean and the original
    version can be found [here](http://cnx.org/content/m17568/latest/).

-   **Web Media: Khan Academy’s “Central Limit Theorem”**
    Link: Khan Academy’s [“Central Limit
    Theorem”](https://www.khanacademy.org/math/probability/statistics-inferential/sampling_distribution/v/central-limit-theorem) (YouTube)  
        
     Instructions: Watch the video. The presenter gives an excellent
    development of The Central Limit Theorem.  
        
     Watching this lecture should take approximately 10 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP III.D.2
    -   AP III.D.3

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Web Media: Khan Academy’s “Sampling Distribution of the Sample
    Mean”**
    Link: Khan Academy’s [“Sampling Distribution of the Sample
    Mean”](https://www.khanacademy.org/math/probability/statistics-inferential/sampling_distribution/v/sampling-distribution-of-the-sample-mean) (YouTube)  
      
     Instructions: Watch the video. Part of this video presentation
    includes an exercise that is used to illustrate The Central Limit
    Theorem. You will have an opportunity to go directly to this website
    and do your own exploration. See the activity, “Sampling
    Distribution,” at the end of this subunit.  
        
     Watching this lecture should take approximately 15 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP III.D.2
    -   AP III.D.3 

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Web Media: Khan Academy’s “Sampling Distribution of the Sample
    Mean 2”**
    Link: Khan Academy: [“Sampling Distribution of the Sample Mean
    2”](https://www.khanacademy.org/math/probability/statistics-inferential/sampling_distribution/v/sampling-distribution-of-the-sample-mean-2) (YouTube)  
      
     Instructions: Watch the video. There is no need to take notes. The
    presenter further discusses the sampling distribution of the mean in
    an informal and intuitive way.  
      
     Watching this lecture should take approximately 15 minutes.  
      
     Standards Addressed (Common Core and AP):  

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP III.D.2
    -   AP III.D.3

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Web Media: YouTube: Khan Academy’s “Standard Error of the Mean”**
    Link: YouTube: Khan Academy’s [“Standard Error of the
    Mean”](https://www.khanacademy.org/math/probability/statistics-inferential/sampling_distribution/v/standard-error-of-the-mean) (YouTube)  
      
     Instructions: Watch the video. Recognize that the standard error of
    the mean is the “new” standard deviation, with
    symbol *O<sub>x̅</sub>*, resulting from using a sample of a specified
    size. It is related to the “old” standard deviation, with
    symbol *O<sub>x</sub>*. Watch how the presenter develops the concept
    of the standard error.  
        
     Watching this lecture should take approximately 20 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP III.D.2
    -   AP III.D.3

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Web Media: Khan Academy’s “Sampling Distribution Example
    Problem”**
    Link: Khan Academy’s [“Sampling Distribution Example
    Problem”](https://www.khanacademy.org/math/probability/statistics-inferential/sampling_distribution/v/sampling-distribution-example-problem) (YouTube)  
        
     Instructions: Watch the video. The presenter takes you step-by-step
    through a problem about the probability of running out of water on a
    camping trip. You will use the sampling distribution concept to
    answer the question. Have your calculator or your table of standard
    normal probabilities handy.  
        
     Watching this lecture should take approximately 15 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP III.D.2
    -   AP III.D.3

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Checkpoint: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 7.2: The Central
    Limit Theorem”; partially adapted from David Lane’s *Online
    Statistics Education: A Multimedia Course of Study* and CK-12:
    *Advanced Probability and Statistics***
    Link: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: [“Section 7.2: The Central
    Limit
    Theorem”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Work on the review questions at the end of Section
    7.2. Use appropriate formulas and notation as you work. For the
    correct answers, [click
    here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2013/07/K12MATHAPSTATS-Unit-7-Flexbook-Answers-Sec.-7.2-FINAL.pdf).  
        
     Completing the review questions should take approximately 1 hour.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP III.D.1
    -   AP III.D.2
    -   AP III.D.3
    -   AP III.D.6
    -   AP IV.A.1
    -   AP IV.A.2
    -   AP IV.A.3
    -   AP IV.A.4
    -   AP IV.A.6

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

-   **Activity: Rice Virtual Lab in Statistics: “Sampling
    Distribution”**
    Link: Rice Virtual Lab in Statistics: [“Sampling
    Distribution”](http://www.onlinestatbook.com/stat_sim/sampling_dist/index.html) (Java)  
        
     Instructions: Play with the applet. Helpful hints for using the
    applet are on the right side of the introductory screen. This is the
    identical applet that was used in the Khan Academy video, “Central
    Limit Theorem.” First, use your mouse to change the shape of the
    parent graph at the top. Make it look as weird as you wish. Then
    take 1,000 samples of size *n* = 5, and see what the resulting
    distribution looks like (it should be roughly normal). Next, clear
    the screen, and this time take 1,000 samples of size *n* = 25. You
    are essentially guaranteed that the distribution of the sample means
    will be normal.  
        
     Note what happens to the standard deviation of the “new” (normal)
    distribution as you increase the sample size. Does the standard
    deviation (standard error) of the new distribution get larger or
    smaller as you increase the sample size?  
        
     Performing this activity should take approximately 30 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP III.D.2
    -   AP III.D.3

    Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**7.3 Confidence Intervals** <span id="7.3"></span> 
*The confidence interval is a statement about the value of an unknown
parameter. Our initial discussion will center on the value of the
unknown value of I, the population mean, or the value of p, the
population proportion. We might randomly sample a group of kindergarten
children and weigh them. The value of the mean weight x̅  is called a
point estimate, and it is an estimate of the true population mean I. But
sometimes, instead of calculating a single value as an estimate, we want
to create an interval, a range of values that might contain the true
population mean. This range of values is called the confidence
interval.*

-   **Explanation: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 7.3: Conﬁdence
    Intervals with z-values”; partially adapted from David Lane’s
    *Online Statistics Education: A Multimedia Course of Study* and
    CK-12: *Advanced Probability and Statistics***
    Link: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: [“Section 7.3: Conﬁdence
    Intervals with
    z-values”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Read Section 7.3. This is a challenging section, and
    you will want to read actively, with pencil, paper, and calculator
    on hand. You will encounter confidence intervals in later parts of
    the course, so make sure you work through each example carefully.  
        
     Reading this section and taking notes should take approximately 1
    hour and 30 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   [CCSS.ELA-Literacy.RST.11-12.2](http://www.corestandards.org/ELA-Literacy/RST/11-12/2/)
    -   AP IV.A.1
    -   AP IV.A.2
    -   AP IV.A.3
    -   AP IV.A.4
    -   AP IV.A.6

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

-   **Web Media: SOPHIA: Ryan Backman’s “Confidence Intervals”**
    Link: SOPHIA: Ryan Backman’s [“Confidence
    Intervals”](http://www.sophia.org/confidence-intervals/confidence-intervals--4-tutorial) (HTML5)  
        
     Instructions: Watch the video, which provides a basic overview of a
    confidence interval.  
        
     Watching this video should take approximately 5 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP IV.A.1
    -   AP IV.A.2
    -   AP IV.A.3
    -   AP IV.A.4
    -   AP IV.A.6

    Terms of Use: This resource is licensed under a [Creative
    Commons Attribution-NonCommercial 3.0
    Unported](http://creativecommons.org/licenses/by-nc/3.0/)<span
    style="line-height: 19.1875px;">.</span> 

-   **Web Media: YouTube: Barbara Illowsky and Susan Dean’s “Confidence
    Intervals”**
    Link: YouTube: Barbara Illowsky and Susan Dean’s [“Confidence
    Intervals”](http://www.youtube.com/watch?v=4Nl0oZmD4M0) (YouTube)  
        
     Instructions: Watch the video. Stop at the end of the confidence
    interval for a proportion (17:20). The presenter gives a superb
    introduction to the point estimate, the margin of error, and
    confidence intervals. You will need paper, pencil, and either your
    calculator or table of standard normal values.  
        
     Make sure that you can identify the difference between a point
    estimate and an interval estimate. Define the margin of error, the
    confidence level, and a confidence interval. Know the meaning and
    use of the symbol *α*.  
        
     Completing these activities should take approximately 20 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   [CCSS.ELA-Literacy.RST.11-12.7](http://www.corestandards.org/ELA-Literacy/RST/11-12/7/)
    -   AP IV.A.1
    -   AP IV.A.3
    -   AP IV.A.4
    -   AP IV/A.6

    Terms of Use: This work is licensed under a [Creative Commons
    Attribution 2.0 Generic
    License](http://creativecommons.org/licenses/by/2.0/). It is
    attributed to Barbara Illowsky and Susan Dean and the original
    version can be found [here](http://cnx.org/content/m17569/latest/).

-   **Web Media: Khan Academy’s “Confidence Interval 1”**
    Link: Khan Academy’s [“Confidence Interval
    1”](https://www.khanacademy.org/math/probability/statistics-inferential/confidence-intervals/v/confidence-interval-1) (YouTube)  
        
     Instructions: Watch the video. The presenter gives a “reverse”
    introduction to the idea of a confidence interval with the apple
    example. Don't let this confuse you.  
        
     Watching this lecture should take approximately 15 minutes.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP IV.A.1
    -   AP IV.A.3
    -   AP IV.A.4
    -   AP IV/A.6

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Web Media: Khan Academy’s “Confidence Interval Example”**
    Link: Khan Academy’s [“Confidence Interval
    Example”](https://www.khanacademy.org/math/probability/statistics-inferential/confidence-intervals/v/confidence-interval-example) (YouTube)  
      
     Instructions: Watch the video. The first part of this video is a
    straightforward example about the calculation of a confidence
    interval for a population proportion. Pay close attention to the
    calculation of this confidence interval.  
        
     Watching this lecture should take approximately 20 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP IV.A.1
    -   AP IV.A.3
    -   AP IV.A.4
    -   AP IV/A.6

    Terms of Use: This resource is licensed under a[Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    attributed to Khan Academy.

-   **Web Media: SOPHIA: Bob Kibler’s “Confidence Interval for the
    Mean - s.d of Population Known or Large Sample Size”**
    Link: SOPHIA: Bob Kibler’s [“Confidence Interval for the Mean - s.d
    of Population Known or Large Sample
    Size”](http://www.sophia.org/confidence-interval-for-the-mean-sd-of-population-tutorial) (HTML5)  
        
     Instructions: Watch the video. This video takes you through the
    determination of a confidence interval for the mean. Scroll down to
    the “Notes” section below the video screen. Download, print, and
    fill out the notes pages as you watch the video. After you finish,
    scroll down to the “Do I get it?” screen and answer the problems,
    ignoring the “Student ID” box. You do not need to click “submit,”
    but should check your work with the answers posted just below the
    “Do I get it?” screen.  
        
     Completing these activities should take approximately 45 minutes.  
        
     Standards Addressed (*Common Core and AP*):  

    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   AP IV.A.1
    -   AP IV.A.3
    -   AP IV.A.4
    -   AP IV/A.6

    Terms of Use: This resource is licensed under a [Creative
    Commons Attribution-NonCommercial 3.0
    Unported](http://creativecommons.org/licenses/by-nc/3.0/)<span
    style="line-height: 19.1875px;">.</span>

-   **Checkpoint: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: “Section 7.3: Conﬁdence
    Intervals with z-values”; partially adapted from David Lane’s
    *Online Statistics Education: A Multimedia Course of Study* and
    CK-12: *Advanced Probability and Statistics***
    Link: The Saylor Foundation’s Flexbook: Jill Schmidlkofer’s
    *Advanced Probability and Statistics*: [“Section 7.3: Conﬁdence
    Intervals with
    z-values”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2013/07/Statistics-FlexBook-20130714-FINAL.pdf);
    partially adapted from David Lane’s *Online Statistics Education: A
    Multimedia Course of Study* and CK-12: *Advanced Probability and
    Statistics* (PDF)  
        
     Instructions: Work on the review questions at the end of Section
    7.3. Both questions deal with point estimates for confidence
    intervals for proportions.  For detailed solutions, [click
    here](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2013/07/K12MATHAPSTATS-Unit-7-Flexbook-Answers-Sec.-7.3-FINAL.pdf).  
        
     Completing the review questions should take approximately 1 hour.  
        
     Standards Addressed (*Common Core and AP*):

    -   [CCSS.Math.Content.HSS-IC.A.1](http://www.corestandards.org/Math/Content/HSS/IC/A/1)
    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   [CCSS.ELA-Literacy.RST.11-12.2](http://www.corestandards.org/ELA-Literacy/RST/11-12/2/)
    -   [CCSS.ELA-Literacy.RST.11-12.6](http://www.corestandards.org/ELA-Literacy/RST/11-12/6/)
    -   [CCSS.ELA-Literacy.RST.11-12.7](http://www.corestandards.org/ELA-Literacy/RST/11-12/7/)
    -   [CCSS.ELA-Literacy.RST.11-12.9](http://www.corestandards.org/ELA-Literacy/RST/11-12/9/)
    -   AP III.D.1
    -   AP III.D.2
    -   AP III.D.3
    -   AP III.D.6
    -   AP IV.A.1
    -   AP IV.A.2
    -   AP IV.A.3
    -   AP IV.A.4
    -   AP IV.A.6

    Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/). It is
    adapted from works attributed to David Lane and CK-12, which can be
    found [here](http://onlinestatbook.com/) and
    [here](http://www.ck12.org/book/CK-12-Advanced-Probability-and-Statistics-Concepts/).

**Unit 7: Assessment** <span id="7.4"></span> 
-   **Assessment: The Saylor Foundation’s “Unit 7 Assessment”**
    Link: The Saylor Foundation’s [“Unit 7
    Assessment”](http://school.saylor.org/mod/quiz/view.php?id=1630) (HTML)  
        
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
    -   [CCSS.Math.Content.HSS-IC.B.4](http://www.corestandards.org/Math/Content/HSS/IC/B/4)
    -   [CCSS.ELA-Literacy.RST.11-12.2](http://www.corestandards.org/ELA-Literacy/RST/11-12/2/)
    -   [CCSS.ELA-Literacy.RST.11-12.6](http://www.corestandards.org/ELA-Literacy/RST/11-12/6/)
    -   [CCSS.ELA-Literacy.RST.11-12.7](http://www.corestandards.org/ELA-Literacy/RST/11-12/7/)
    -   [CCSS.ELA-Literacy.RST.11-12.9](http://www.corestandards.org/ELA-Literacy/RST/11-12/9/)
    -   AP III.D.1
    -   AP III.D.2
    -   AP III.D.3
    -   AP III.D.6
    -   AP IV.A.1
    -   AP IV.A.2
    -   AP IV.A.3
    -   AP IV.A.4
    -   AP IV.A.6


