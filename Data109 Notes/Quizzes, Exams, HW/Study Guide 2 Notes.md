
#21 Binomial stuff.

Multiple choice quiz, 4 options, 1 correct answer (probability is .25). 10 questions.
A: prob of getting NO questions right 
B: prob of getting exactly 1 quesiton
C: prob of getting 4+ questions right

Use binomial formula (P(X = k) = (n choose k) (p)^k (1-p)^n-k 
	Notes on study guide: correct

There IS CODE to do this.
	A: dbinom(0, 10, .25)
	B: dbinom(1,10,.25)
	C: pbinom(1,10, .25)

dbinom is *just* the number.
pbinom is up to the number.

