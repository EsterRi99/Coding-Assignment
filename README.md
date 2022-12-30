# Coding-Assignment


#Question 2

2.1

f(σ)=((1.038)^2*((ℯ^(σ*σ))-1))-0.086^2

find_zeros(f, -10000000, 1000000)

#we get: σ= +/- 0.08270998242742104


g(μ)=ℯ^(μ+(0.08270998242742104^2/2))-1.038

find_zeros(g, -10000000, 1000000)

#we get the same result whether σ is positive or negative as the value is squared

#result is: μ= 0.03387531414712473

