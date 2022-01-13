# Hard_2240_PlumTree

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/Hard_2240_PlumTree/blob/main/2240_pro.PNG)

## What Algorithm should I use?

dynamic programming

## What was the key point and the hard part?

*Failed to solve it by myself*

This problem is good example for me to understand to use 3 dim array dp.

In here there is 3 conditions. Time , Move , current location.

dp[Time][Move][location] is dp.

At first , 자두 start a first tree.

If first plum drop from the first tree, 자두 don't have to move and she can eat plum.

If second plum drop from the second tree, she can move and eat the plum or don't move and don't eat the plum.

After that , we have to compare (자두 move and eat the plum , 자두 don't move and don't eat the plum , 자두 don't have to move and can eat the plum.)

There is some condition we have to check.

If 자두 never moved, (Move == 0) and plum drop at her current location, 자두 can eat the plum and we should not consider other options.

This is because of there is no possibility for 자두 had moved from other side.

Also, at last, we have to check other side because 자두 can have max plum if she don't eat the las plum. (This means we cannot find max case if we compare max value in the if statement)


## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
