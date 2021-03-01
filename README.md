Week 2 Quiz: Evaluating machine learning models


Question 1
What is the sensitivity and specificity of a pneumonia model that always outputs positive?  In other words, the models says that every patient has the disease.


Answer: 
sensitivity = 1.0, specificity = 0.0


Question 2
In some studies, you may have to compute the Positive predictive value (PPV) from the sensitivity, specificity and prevalence.  

Given a sensitivity = 0.9, specificity = 0.8, and prevalence = 0.2, what is the PPV (positive predictive value)? 

HINT: please check the reading item "Calculating PPV in terms of sensitivity, specificity and prevalence"



Answer: 
0.53


Question 3
If sensitivity = 0.9, specificity = 0.8, and prevalence = 0.2, then what is the accuracy? 

Hint: You can watch the video "Sensitivity, Specificity and Prevalence" to find the equation.



Answer:
0.82


Question 4
What is the sensitivity and specificity of a model which randomly assigns a score between 0 and 1 to each example (with equal probability) if we use a threshold of 0.7?  


Answer:
Sensitivity = 0.3, Specificity = 0.7



Question 5
What is the PPV and sensitivity associated with the following confusion matrix?


Answer:
PPV = 0.3,  Sensitivity = 0.6



Question 6
You have a model such that the lowest score for a positive example is higher than the maximum score for a negative example. What is its ROC AUC?  

HINT 1: watch the video “Varying the threshold”.

HINT 2: draw a number line and choose values for the score that is the lowest prediction for any positive example, and choose another number that is the score for the highest prediction for any negative example.  Draw a few circles for “positive” examples and a few “x” for the negative examples.  What do you notice about the model’s ability to identify positive and negative examples?


Answer:
1.0




Question 7
For every specificity, as we vary the threshold, the sensitivity of model 1 is at least as high as model 2. Which of the following must be true? 


Answer:

The ROC of model 1 is at least as high as model 2





Question 8
You want to measure the proportion of people with high blood pressure in a population. You sample 1000 people and find that 55% have high blood pressure with a 90% confidence interval of (50%, 60%). What is the correct interpretation of this result?  

HINT: Please watch the video "Confidence interval" to help you answer this question.

Answer:

If you repeated this sampling, the true proportion would be in the confidence interval about 90% of the time







Question 9
One experiment calculates a confidence interval using 1000 samples, and the another computes it using 10000 samples. Which interval do you expect to be tighter (assume they use the normal approximation)?  

Answer:
10,000 samples
