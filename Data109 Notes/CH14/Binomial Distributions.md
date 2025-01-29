### Binomial Setting

1. N observations( fixed )
2. all n obs are independent
3. All observations are either a success or failure
4. all N observations have the same probability of success

Ex: Flipping a coin
	n = 80
	heads = success
	p = 0.50

### Binomial Distribution
Requires:
	A count of successes (X)

A count of successes has a binomial distribution if it meets the criteria for the binomial setting

Ex: Farmers
	P = 0.11
	n = 10,000 bushels
	inspector takes SRS of 10

Because the inspector takes SRSes and discards potentially bad bushels, the observations have a shifting chance of success, and thus are not independent of each other. This is Not A Binomial Distribution

Ex: Blood Types
For any pair of parents
	p = 0.25 for children to have 0 type blood
	n = 5

### Binomial Probabilities 
N = Number of Observations
P = probability of Success
X = Count of Successes 

Recall: Factorials = n! 
	n! = n(n-1)(n-2) until 1
		ex 5! = 5 4 3 2 1


#### Binomial Distribution Equation

P(X=K) = (n choose k) * p(k) * (1-p)^n-k

n = 14
p = 0.70

P(x=8) = (14 choose 8) * (0.70)^8 * (1-0.7)^14-8

= (14 choose 8) * (0.7)^8 * (0.30)^6 

14 choose 8 = 14! / 8! * 6!

### Binomial Coefficient
	(n/k) = n choose k 
	= n! / k!(n-k)!

n!/ o! * n! = 1

n! / 1 = n