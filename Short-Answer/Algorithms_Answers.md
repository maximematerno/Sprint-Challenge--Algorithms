#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) This loop will increment from 0, 9, 18, 27, and the loop runs 3 times. So the loop will run 'n' number of times. It's linear, so this would be a case of 'O(n)'.


b) This one contains two loops. The for loop will run for i in range(n) and continue to increment by 1. And the inner while loop will run within the for loop while j is less than n and double every time. it should be O(nlog(n)).


c) This one has a recursive loop. It's only going to run for n number of times. This is linear in time complexity, so O(n). 

## Exercise II

We are searching for a range, I would assume that a binary search would be a good approach.

If the parameter you're passing is n(number of floors), start with n // 2, and hypotehtically drop it from half way down the building(n // 2). If it breaks then you know the max height is less than n // 2, if it does not break then you know the max height is above n // 2. and depending on which one contains the breaking point, you'd then divide that half // 2 and repeat the process until reaching the integer indicative of the floor number.

This would be linear, the time complexity would be O(n).




