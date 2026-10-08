# Machine-learning-project-June2026
Project in Machine Learning. Supervised learning using numerical and labeled data from unknown distributions.



## Questions


### 1(a)
Construct a ML pipeline to analyze the ``X_TR``, ``y_TR`` data set. Make sure to motivate choices made in for the pipeline. Investigate the effect of sample size on performance.

**Discuss:**
- Overall and class-specific performance of methods and how you assess this
- Why you think some methods perform better than others on this data set and for different sample sizes
- Particular challenges in this data set that your analysis identified and how you addressed them
- How many features were informative and if this dependend on the method and how you assessed this

### 1(b)
What's a minimum disruption to the given data set that will make some methods perform worse? This should not be just adding noise to the data because that would be the same for all data sets - what is special about the data given to you? Be precise in how you target your data and target your chosen methods.

Implement a disruption technique and illustrate how some methods fail and others are more resilient. Motivate why you chose this specific disruption for you data.

**Discuss:**
- How you chose your disruption approach and why
- Effect on method performance and explain why this is the expected effect
- Stability of assessment


### 1(c)
Is there any evidence of mislabeling in your data set?

**Discuss:**
- How you identified (if any) potentially mislabeled observations
- Verify that this technique works by adding mislabeled observations to your data and showing that you can detect them using this technique



### 2(a)
Use your data and create a much more challenging problem where you have one super-majority class and the rest are tiny minority classes (you choose - but push the limit so this truly is extreme). How does your pipeline perform on this altered data set? Can you alleviate the problem by weighting or oversampling?

**Discuss:**
- Classification metrics
- Effect on performance and why you think this is



### 2(b)
One way to approach this kind of problem is to first run majority-vs-rest and then a multiclass problem for the minority classes. Implement this and investigate if that works for your data set.

**Discuss:**
- Your new pipeline - how well you perform this hiearchical classification
- Which methods you chose for the two levels
- How well this worked for your data set

