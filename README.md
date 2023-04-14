# CHD1E
"Brotherhood" competition from Codefun

Story goes like this: LA city, in MNF's world, has a population of approx 1 million people. 1 person, 1 number ranging from 1 <--> 10^9. Males have even numbers, 
and females have the others. There might be dupes but that is how the law works.

Thanh and Cindy will be playing a game. Cindy will be picking number N and putting it into a hotel. The hotel picks K "loots", of which the gender role 
applies. They should have same rates of occruing.

In each turn, 1 player will pick 2 characters (human? loot?). Call them X and Y, and send them to a room in the hotel. These 2 will "breed" and make
new loot, carrying the value of |x-y|. Then they move to a private house. Cindy goes first. Depending on the last character's gender can we decide who is the winner.
Male? Cindy wins. And vice versa. Assuming both players are godlike in logical deductions, Thanh wants to be dumped, Cindy is downbad for boys, how likely it is for Thanh
to be dumped?



SPECS:
Input: 
T for number of tests. \*Enters*|
N, K for aforementioned numbers (0 <--> 10^5) \*Enters*\
N

Output: Probability of Thanh being dumped, with precision of 6 decimal points.

Input:
1
1 1
1

Output:
0.500000
