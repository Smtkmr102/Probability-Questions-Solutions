# Probability-Questions-Solutions
This course introduces combinatorics, the study of counting, which is essential in probability. It explores probability with examples like coins and cards. Covers expectation values, variance, and standard deviation. Discusses common probability distributions, correlation, and regression.
# Question: 
If you roll a standard six-sided die twice (or equivalently, roll two dice), how many different possible ordered outcomes are there?
# Solution
* There are six possibilities for what the first die shows, and six for the second.
* So there are 6 * 6 = 36 possibilities in all. If you want to list them out,
* they are shown in Table
  
  ![image](https://github.com/Smtkmr102/Probability-Questions-Solutions/assets/110372120/d22ea6fd-6def-4a85-b55d-3a41802e7262)

* Since we are assuming that the order matters, a 2,5 is different from a 5,2. That is, rolling a 2 on the first die (or, say, the left die if you're rolling both at once) and then a 5 on the second die (or the right die) is different from rolling a 5 and then a 2.
* All 36 possibilities in the table account for these distinct ordered outcomes.
# Remark 
 * What is the probability of obtaining a sum of 7 when rolling two dice?
 * If we look at the above Table, we see that six different outcomes yield a sum of 7.
 * They are 1,6; 2,5; 3,4; 4,3; 5,2; 6,1. Since all 36 possibilities are equally likely (because the probability of any number showing up on any roll is the same, namely 1/6), and since six of the possibilities     
   yield the desired sum of 7, the probability of rolling a sum of 7 is 6/36 = 1/6 ≈ 16.7%.
