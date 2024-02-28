# Chapter1. Combinatorics
 Combinatorics is the study of how to count things. By “things” we mean the various
 combinations, permutations (different orderings), subgroups, and so on, that can be
 formed from a given set of objects/people/etc.
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
# Question 
 If you flip a coin four times (or equivalently, flip four coins), how many different possible ordered outcomes are there?
# Solution
* There are two possibilities (Heads or Tails) for what the first coin shows, and two  for the second, and two for the third, and two for the fourth.
 So there are
 2 · 2 · 2 · 2 = 24 = 16 possibilities in all.
* If you want to list them out, they are shown
  in Table
  ![image](https://github.com/Smtkmr102/Probability-Questions-Solutions/assets/110372120/6047ae62-6e5f-4435-9065-a6e4cec79462)
  
 * We have grouped the various possibilities into two columns according to whether the first coin shows a Head or a Tail.
 * Each column has eight entries because 2^3 = 8 is the number of possible outcomes for three coins.
 * (Just erase the first entry in each four-coin outcome, and then each column gives the eight possible three-coin outcomes.)
 * Similarly, it’s easy to see why five coins yield 2^5 = 32 possible outcomes.
 * We just need to take all 16 of the four-coin outcomes and tack on an H at the beginning, and then take all 16 again and tack on a T at the beginning.
 * This gives 2.16 = 32 possible five-coin outcomes.
# Remark
* What is the probability of obtaining exactly two Heads in four coin flips?
* Looking at Table 1.6, we see that six outcomes have two Heads.
* They are HHTT, HTHT, HTTH, THHT, THTH, and TTHH.
* Since all 16 possibilities are equally likely (because the probability of either letter showing up on any flip is the same, namely 1/2), and since six of the possibilities yield the desired 
  the outcome of two Heads, the probability of obtaining two Heads is 6/16 = 3/8 = 37.5%.
# Question
How many different ordered pairs of people can be chosen from a group of five people?
# Solution
 Let the five given people be labeled A, B, C, D, E. 
 We’ll write down all of the possible ordered pairs of letters, temporarily including repetitions, even though we can’t actually repeat a person. 
 As we saw in Table, there are five possibilities for the first entry, and also five possibilities for the second entry, so we end up with the 5 by 5 square of possible pairs shown in Table.
 
 ![image](https://github.com/Smtkmr102/Probability-Questions-Solutions/assets/110372120/0d9098ce-90a7-4a19-805d-dd3f772a3d22)
 
* The five pairs with repeated letters, highlighted along the diagonal of the square, are not allowed, as the committee members must be different.
* Consequently, the total number of ordered pairs is calculated as 5^2 − 5, resulting in 20 permissible pairs.
* In a more general context, if we wish to select an ordered pair from a group of N people, we can visualize creating an N by N square, providing N^2 pairs.
* To account for the restriction of pairs with repeated letters, we subtract the N pairs along the diagonal, leading to N^2 − N pairs.
* This expression can be further written as N(N − 1), representing the general formula for selecting an ordered pair without repetition from a group of N individuals.
# Remark 
 * If we have two seats that need to be filled with the two committee members, then there are five possibilities for who goes in the first seat. And then for each of these
   possibilities, there are four possibilities for who goes in the second seat, because there are only four people left. So there are 5 · 4 = 20 ways to plop down the two people
   in the two seats.
* This is exactly the same reasoning as with the N! ways to assign N people to N seats, except that we’re stopping the assignment process after two seats.So wehave only the product 5 · 4  
  instead of the product 5 · 4 · 3 · 2 · 1. The number of ordered pairs we can pick from five people is therefore 5 · 4 = 20, as we found above.The preceding reasoning generalizes easily to  
  the case where we pick ordered pairs from N people. There are N possibilities for who goes in the first seat, and then for
  each of these, there are N − 1 possibilities for who goes in the second seat. The total number of possible ordered pairs is therefore N(N − 1).
