Advanced Hailstone series for the following formula:
where if X is even : Xn{next number} = Xn-1{current number}/2
and if X is odd : Xn{next number} = a(Xn-1{current number})+b
a and b are from 1-10, x is from 1 to 1000
ifthe sequence satisfies the Hailstone series, it will converge to 1 ultimately, if it is not, considering that it does not converge in a 1000 iteration of finding Xn, it will not converge to 1. The code finds all such sequences those converge to 1.
