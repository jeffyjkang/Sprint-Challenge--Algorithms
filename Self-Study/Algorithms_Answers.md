Add your answers to the Algorithms exercises here.

a. constant = 0, while ( constant< n^3>)
constant = constant + n^2
when n =2 , runs twice
when n =5 runs 5 times

O(n) is n times a constant, drop constant.

n =5
0 < 125:
a = 0 + 25
25<125
50<125
75<125
100<125
125<125

answer: O(n)

b. for i in range(5) 50: 500:

for each nested loop each iteration is being multiplied per nest
therefore size of nest, or depth is the power of the O(n)
last nest is constant and is dropped

for i in range(5):
i +=1 , increase by 1 each iteration
for j in range(i+1, 5):
j+=1, increasing by 1 each iteration
for k in range( j +1 , 5):
k+=1 increasing by 1 each iteration
for l in range(k+1, 10 +k):
l+=1 increasing by 1 each iteration
sum +=1

answer: O(n^3)

c.
return 0 or 2+ bunnyEars so drop constant bunnies
O(n)

exercise 2:
n story building, eggs
egg is broken if floor f or higher
egg is not broken if less than floor f

lets say we have 10 stories
since the stories are obviously sorted what i would want to do is do
a, binary search,
pick an index, in this case the middle, so 5th story
drop an egg, if it breaks go lower, if not got higher
from index of 5th story, 3rd story if lower,
if higher, 8th story,
and constantly reiterate

O(logn)
