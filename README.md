# homwork-2

1)
We can use the combination formula to solve this problem. The number of ways to choose 4 students out of 12 for the first test is:
C(12,4) = 495
After these 4 students have taken the first test, there are only 8 students left to choose from for the second test. The number of ways to choose 4 students out of 8 for the second test is:
C(8,4) = 70
Finally, after 8 students have taken the first two tests, there are only 4 students left to choose from for the third test. The number of ways to choose 4 students out of 4 for the third test is:
C(4,4) = 1
To find the total number of ways that the tests can be taken, we multiply these three numbers together:
495 x 70 x 1 = 34,650


2)
   2*3*1=6
   we can see all six permutations: abc, acb, bac, bca, cab, and cba


3)
A) The total number of ways to select two items from a box containing 12 items is:
n = 12C2 = (12! / (2! * 10!)) = 66
Let A be the event that both items are defective. There are 4 defective items in the box, so the number of ways to select two defective items is:
m(A) = 4C2 = (4! / (2! * 2!)) = 6
Therefore, the probability of selecting two defective items is:
P(A) = m(A) / n = 6 / 66 = 1/11
Let B be the event that both items are non-defective. There are 8 non-defective items in the box, so the number of ways to select two non-defective items is:
m(B) = 8C2 = (8! / (2! * 6!)) = 28
Therefore, the probability of selecting two non-defective items is:
P(B) = m(B) / n = 28 / 66 = 14/33
Therefore, P(A) = 1/11 and P(B) = 14/33.
B) P(at least one item is defective) = 1 - P(no item is defective)
To find P(no item is defective), we need to count the number of ways to select two non-defective items from the box. We know that there are 8 non-defective items in the box, so the number of ways to select two non-defective items is:
m = 8C2 = (8! / (2! * 6!)) = 28
Therefore, the probability of selecting two non-defective items is:
P(no item is defective) = m / n = 28 / 66
Substituting this value into the formula above, we get:
P(at least one item is defective) = 1 - P(no item is defective) = 1 - (28 / 66) = 38/66
the probability that at least one item is defective is 38/66.

4)
We can use the formula for probability:
P(event) = (number of favorable outcomes)/(total number of possible outcomes)
(i) To find the probability that none of the three selected items is defective, we need to choose 3 items from the 10 non-defective ones. The total number of possible outcomes is choosing 3 items from all 15. Therefore,
P(none defective) = (number of ways to choose 3 non-defective items)/(total number of ways to choose 3 items)
= (C(10,3))/(C(15,3))
= (120)/(455)= 24/91 =0.2637
(ii) To find the probability that exactly one item of the three items is defective, we need to choose one defective item and two non-defective ones. There are C(5,1) ways to choose one defective item and C(10,2) ways to choose two non-defective ones. Therefore,
P(exactly one defective) = (number of ways to choose 1 defective and 2 non-defective items)/(total number of ways to choose 3 items)
= (C(5,1)*C(10,2))/(C(15,3))
= (5*45)/(455)
= 45/91 =0.4945
(iii) To find the probability that at least one item of the three items is defective, we can use the complement rule: P(at least one defective) = 1 - P(none defective). Therefore,
P(at least one defective) = 1 - P(none defective)
= 1 - (C(10,3))/(C(15,3))
= 1 - (120)/(455)
= 67/91 = 0.7363

5)
P(boy) = number of boys / total number of students = 10 / 30 = 1/3 
The probability of choosing someone from Mansoura randomly is: 
P(Mansoura) = number of Mansoura students / total number of students = (5+15) / 30 = 2/3
P(boy or Mansoura) = P(boy) + P(Mansoura) - P(boy and Mansoura) 
= (1/3) + (2/3) - (5/30) 
= 20/30 
= 2/3
Therefore, the probability that a person chosen randomly is a boy or from Mansoura university is 2/3.

6)
 (i) P(Ac) = 1 - P(A) = 1 - 3/8 = 5/8
(ii) P(Bc) = 1 - P(B) = 1 - 1/2 = 1/2
(iii) P(Ac intersection Bc) = P((A union B)c) = 1 - P(A union B)
                             = 1 - (P(A) + P(B) - P(A intersection B))
                             = 1 - (3/8 + 1/2 - 1/2)
                             = 5/8 - 1/4
                             = 3/8
(iv) P(Ac union Bc) = P((A intersection B)c)
                            = 1 - P(A intersection B)
                            = 1 - 1/2
                            = 1/2
(v) P(A intersection Bc) = P(Bc|A)*P(A)
                                   =(P(B)-P(B intersection A))/P(A)*P(A)
                                   =(1/2-1/2)/3/8
                                   =0
(vi) Similarly, we can find that 
      P(B intersection Ac)=0

7)
The complement of rolling at least one 7 is rolling no 7s in three rolls. The probability of this happening is (5/6)^3 = 125/216.
Therefore, the probability of rolling at least one 7 in three rolls is:1 - (125/216) = 91/216
8)
The sum of probabilities of all possible outcomes in a sample space is always equal to 1. Therefore:
Σ P(x) = 1
However, in this case, we are given that:
Σ P(x) = k^2 - 8
Therefore:
k^2 - 8 = 1
Solving for k, we get:
k^2 = 9
k = ±3
Therefore, the value of k is ±3.


9)
P(A′ ∩ B′) represents the probability of outcomes that are not in A and not in B. This can be calculated as follows: 
P(A′ ∩ B′) = 1 - P(A ∪ B) 
Since A and B are mutually exclusive, their union is simply the sum of their probabilities: 
P(A ∪ B) = P(A) + P(B) = 0.35 + 0.45 = 0.8 
Therefore, 
P(A′ ∩ B′) = 1 - P(A ∪ B) 
= 1 - 0.8 
= 0.2
