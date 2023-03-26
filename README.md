# Task2-Probability_-Dr-samir-

1- nCr = n! / r!(n-r)!

where n is the total number of students in the class and r is the number of students taking each test.

So in this case, we have n = 12 and r = 4. Therefore, we can calculate the number of ways as follows:

12C4 * 8C4 * 4C4 = (12! / (4! * 8!)) * (8! / (4! * 4!)) * (4! / (4! * 0!)) = 495 * 70 * 1 = 34650

Therefore, there are 34650 ways that 12 students in a class can take 3 different tests if 4 students are to take each test.

2-   a       b       c
         |       |       |
        ---     ---     ---
       |   |   |   |   |   |
       b   c   a   c   a   b
       |   |   |   |   |   |
       --- --- --- --- --- ---
        |   |   |   |   |   |
        c   b   b   a   c   a
Each path from the root node to a leaf node represents one possible permutation of (a, b, c). Therefore, there are 3 * 2 * 1 = 6 permutations of (a, b, c).

3- (A) The total number of ways to select two items from a box containing 12 items is:

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

(B):  P(at least one item is defective) = 1 - P(no item is defective)

To find P(no item is defective), we need to count the number of ways to select two non-defective items from the box. We know that there are 8 non-defective items in the box, so the number of ways to select two non-defective items is:

m = 8C2 = (8! / (2! * 6!)) = 28

Therefore, the probability of selecting two non-defective items is:

P(no item is defective) = m / n = 28 / 66

Substituting this value into the formula above, we get:

P(at least one item is defective) = 1 - P(no item is defective) = 1 - (28 / 66) = 38/66

Therefore, the probability that at least one item is defective is 38/66.

4- (A): The total number of ways to select three items from a box containing 15 items is:

n = 15C3 = (15! / (3! * 12!)) = 455

Let A be the event that none of the three selected items is defective. There are 10 non-defective items in the box, so the number of ways to select three non-defective items is:

m(A) = 10C3 = (10! / (3! * 7!)) = 120

Therefore, the probability of selecting three non-defective items is:

P(A) = m(A) / n = 120 / 455

Therefore, the probability that none of the three selected items is defective is 24/91.

(B): Let B be the event that exactly one item of the three items is defective. We can count the number of ways to select one defective item and two non-defective items as follows:

Number of ways to select one defective item = 5C1 = 5 Number of ways to select two non-defective items = 10C2 = (10! / (2! * 8!)) = 45

Therefore, the number of ways to select exactly one defective item is:

m(B) = 5 * 45 = 225

Therefore, the probability of selecting exactly one defective item is:

P(B) = m(B) / n = 225 / 455

Therefore, the probability that exactly one item of the three items is defective is 225/455.

(C):  P(at least one item is defective) = 1 - P(no item is defective)

To find P(no item is defective), we need to count the number of ways to select three non-defective items from the box. We know that there are 10 non-defective items in the box, so the number of ways to select three non-defective items is:

m = 10C3 = (10! / (3! * 7!)) = 120

Therefore, the probability of selecting three non-defective items is:

P(no item is defective) = m / n = 120 / 455

Substituting this value into the formula above, we get:

P(at least one item is defective) = 1 - P(no item is defective) = 1 - (120 / 455) = 335/455

Therefore, the probability that at least one item of the three items is defective is 335/455.

5- Let’s first calculate the number of boys and girls from Mansoura university. Since half the boys and half the girls are from Mansoura, we have:

Number of boys from Mansoura = 10 / 2 = 5 Number of girls from Mansoura = 20 / 2 = 10

The total number of people in the class is 10 + 20 = 30. Therefore, the probability that a person chosen randomly is a boy or from Mansoura university is:

P(boy or from Mansoura) = P(boy) + P(from Mansoura) - P(boy and from Mansoura)

where P(boy) is the probability of choosing a boy, P(from Mansoura) is the probability of choosing someone from Mansoura, and P(boy and from Mansoura) is the probability of choosing a boy from Mansoura.

We know that there are 10 boys and 30 people in total. Therefore, the probability of choosing a boy is:

P(boy) = 10 / 30 = 1/3

Similarly, we know that there are 15 people (5 boys and 10 girls) from Mansoura and 30 people in total. Therefore, the probability of choosing someone from Mansoura is:

P(from Mansoura) = 15 / 30 = 1/2

Finally, we know that there are 5 boys from Mansoura and 30 people in total. Therefore, the probability of choosing a boy from Mansoura is:

P(boy and from Mansoura) = 5 / 30 = 1/6

Substituting these values into the formula above, we get:

P(boy or from Mansoura) = P(boy) + P(from Mansoura) - P(boy and from Mansoura) = (1/3) + (1/2) - (1/6) = 5/6

Therefore, the probability that a person chosen randomly is a boy or from Mansoura university is 5/6.

6- (A):  The complement of an event A is the event that A does not occur. Therefore:

P(A′) = 1 - P(A)

We are given that:

P(A) = 3/8
P(A′) = 1 - (3/8) = 5/8

(B):  P(B′) = 1 - P(B)

We are given that:

P(B) = 1/2

Therefore:

P(B′) = 1 - (1/2) = 1/2

(C):  Using De Morgan’s law, we can write:

(A′ ∩ B′) = (A ∪ B)′

Therefore:

P(A′ ∩ B′) = P((A ∪ B)′)

We are given that:

P(A ∩ B) = 1/2

Therefore:

P(A ∪ B) = P(A) + P(B) - P(A ∩ B) = (3/8) + (1/2) - (1/2) = 7/8

Therefore:

P((A ∪ B)′) = 1 - P(A ∪ B) = 1 - (7/8) = 1/8

(D): P((A ∩ B)′) = 1 - P(A ∩ B) = 1 - (1/2) = 1/2

(E):  P(A ∩ B) = 1/2

Using De Morgan’s law, we can write:

B′ = (A ∩ B)′ ∪ (A′ ∩ B)′

Therefore:

P(B′) = P((A ∩ B)′ ∪ (A′ ∩ B)′)

Since A and B are not necessarily independent events, we cannot use the formula P(A ∩ B) = P(A)P(B) to find P(A′ ∩ B).

However, we can use the formula:

P(A ∪ B) = P(A) + P(B) - P(A ∩ B)

Therefore:

P(A′ ∩ B) = P(B) - P(A ∩ B)

Substituting the given values, we get:

P(A′ ∩ B) = (1/2) - (1/2) = 0

(F):  0

7- The probability of rolling a 7 with two dice is 6/36 = 1/6. Therefore, the probability of not rolling a 7 with two dice is 5/6.

The probability of not rolling a 7 in three rolls is (5/6) * (5/6) * (5/6) = 125/216.

8- The sum of probabilities of all possible outcomes in a sample space is always equal to 1. Therefore:

Σ P(x) = 1

However, in this case, we are given that:

Σ P(x) = k^2 - 8

Therefore:

k^2 - 8 = 1

Solving for k, we get:

k^2 = 9

k = ±3

Therefore, the value of k is ±3.

9- If A and B are mutually exclusive events, then P(A ∩ B) = 0. This is because if A and B are mutually exclusive, then they cannot occur at the same time.

The complement of an event A is the event that A does not occur. Therefore:

A′ = 1 - P(A) B′ = 1 - P(B)

We want to find P(A′ ∩ B′). Using De Morgan’s law, we can write:

A′ ∩ B′ = (A ∪ B)′

Therefore:

P(A′ ∩ B′) = P((A ∪ B)′)

Since A and B are mutually exclusive, we have:

A ∪ B = A + B

Therefore:

P((A ∪ B)′) = 1 - P(A + B)

Since A and B are mutually exclusive, we have:

P(A + B) = P(A) + P(B)

Therefore:

P((A ∪ B)′) = 1 - (P(A) + P(B))

Substituting the given values, we get:

P(A′ ∩ B′) = 1 - (0.35 + 0.45) = 0.20

Therefore, the probability of rolling at least one 7 in three rolls is:

1 - (125/216) = 91/216

Therefore, the probability that at least one of the three tries you roll a 7 is 91/216.
