### Analysis Of Variance


#### Method For Comparing Any Number Of Means
	Extension/generalization of Ch 21

	Used for Comparing several means against a single categorical variable

If the largest sample S.D is 2x than that of the smallest sample S.D do NOT use ANOVA

Ex.

H0 $\mu1$ = $\mu2$ = $\mu n$

Ha not all mu are the same


### F-test 

F = $variation\ in\ sample\ mean \over variation\ between\ individuals\ within\ the same\ sample$ 
 = $Mean\ square\ for\  groups \over mean\ square\ error$

F = $MSG \over MSE$

Has the dist F(df msg, df mse)

### Degrees Of Freedom
df msg = I -1

df mse = N-I


####Example 

n1 = n = 33, xbar = 40000, st = 5000
n2 = n = 40, xbar = 60000, s = 8000
n3 = n = 36, xbar = 62000, s = 10000


I = 3, df msg = I - 1 = 3 - 1 = 2
N = N1 + N2 + N3 = 33 + 40 + 36 = 109 => df mse = 106

	F(2, 106)