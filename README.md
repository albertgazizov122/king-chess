# king-chess
# Interesting task on "coursera" - King's move! It may seem simple, but I wanted to write down the solution. 
# 1) Initially, formulated the problem on paper 
# 2) Made trial tests for each move 
# 3) I looked again how to use the nested "else-if" operator 
# 4) Wrote the final code and tested it. 
# It's incredible! it turned out to make a working code), although at first the tests did not pass, and I strengthened the solution by writing each option separately.
# code on python
c1 = int(input())
s1 = int(input())
c2 = int(input())
s2 = int(input())
y = 'YES'
n = 'NO'
if c1 - c2 == -1 and s1 - s2 == -1: #Move right
    print(y)
elif c1 - c2 == -1 and s1 - s2 == 0:
    print(y)
elif c1 - c2 == -1 and s1 - s2 == 1:
    print(y)
elif c1 - c2 == 1 and s1 - s2 == -1: #Move left
    print(y)
elif c1 - c2 == 1 and s1 - s2 == 0:
    print(y)
elif c1 - c2 == 1 and s1 - s2 == 1:
    print(y)
elif c1 - c2 == 0 and s1 - s2 == -1: #Move up
    print(y)
elif c1 - c2 == 0 and s1 - s2 == 1: #Move down
    print(y)
else:
    print(n)
