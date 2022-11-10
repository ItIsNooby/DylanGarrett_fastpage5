---
toc: true
layout: post
description: Corrections made to my final assessment
categories: [markdown]
title: Final Corrections
---
![]({{ site.baseurl }}/images/cspfinal.png)

- Q7:
Incorrect. It does not matter if y is 0, but a divide-by-zero error will occur if x is 0.

- Q8: 
Incorrect. The procedure does not interchange the values of j and k. Rather, it returns a new list with the values at indices j and k interchanged. The value of j does not need to be between 0 and k. The procedure only works if j and k are valid list indices, so it is important to document that j and k are both between 1 and LENGTH(numList), inclusive.

- Q11:
Incorrect. The inner loop iterates from index j + 1 to the end of the list, so each element is only compared with the elements that follow it.

- Q13:
Incorrect. The procedure traverses this list and never encounters a positive value. The procedure then returns false as intended.

- Q14:
Incorrect. When numCorrect is 7, the condition numCorrect > 7 evaluates to false. Therefore "check" is displayed as intended.

- Q17:
Incorrect. The Internet was not designed to be completely secure. The protocols used on the Internet do not ensure that all communications are secure.

- Q18:
Incorrect. The Internet is not a data stream.

- Q19: 
Incorrect. The sum is too large to be represented with a 4-bit representation.

- Q23:
Incorrect. While a runner’s position could be estimated using the runner’s average speed, a more accurate representation of the position over time can be achieved using a sampling technique.

- Q30:
Incorrect. The algorithm used to round a numeric value to the nearest integer will be the same regardless of whether the value is stored in a list.

- Q34:
Incorrect. While secondList initially contains ["flute", "violin"], the contents of firstList and secondList are swapped later in the code segment.

- Q36:
Incorrect. This would be the correct solution if i were initialized to 0 instead of 1. This code segment will generate the list [3, 5, 7, 9, 11, 13, 15, 17, 19, 21].

- Q41:
Incorrect. This is the initial value of p. None of the variables has the value 10 after executing the code segment.

- Q44:
Incorrect. For any integer n, the value of n MOD 1 is always 0.

- Q45:
Incorrect. The code segment iterates through each element in the list, incrementing count1 for each positive value and incrementing count2 otherwise. There are only two positive values in the list, not five.

- Q49:
Incorrect. This code segment produces the string "onno".