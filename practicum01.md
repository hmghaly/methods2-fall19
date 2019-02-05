# Welcome to Methods II
This is what we did in the first practicum

# 1 Maximum likelihood estimation: part 1
Compute the maximum likelihood distribution for a single (“fair”) 6-sided die (d6).

# 2 Maximum likelihood estimation: part 2
Estimate the maximum likelihood distribution for adding the values of two (“fair”)
6-sided dice (2d6). For instance, the roll {2, 3} gives the value 2 + 3 = 5.


# 3 The chain rule and the Markov assumption
Let P be a language model (i.e., a probability distribution over word sequences) with a
second-order Markov assumption. Using the chain rule, write out the probability for the sentence
colorless green ideas sleep furiously.

The formula is:
P(colorless, green, ideas,sleep, furiously) =P(colorless)·
P(green | colorless)·
P(ideas | colorless, green)·
P(sleep | green, ideas)·
P(furiously | ideas,sleep)


# 4 Avoiding underflow
Problem Use negative logarithms to compute .00002 · .3.
Hint You can use a calculator or Python for this.
Solution First compute the negative logarithms of the two terms: − log(.00002) ≈ 10.820 and
− log(.3) ≈ 1.204. Their sum is 10.820+1.204 = 12.024. Then compute exp(−12.024) = .000006

# Additional Problems
