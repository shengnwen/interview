# Dream Google

This is a plan which contains eight days tasks of finishing 200 leetcode test questions.

Especially,  I wish this plan can enourage Miss Sheng to complete her goals and then make google dream come true. 

## Encouragement Rule

baseScore = 1.01

The max days is 8. If you complete each days goal (25 questions/day), each day you complete goal you will get a chiose to square the baseScore.

Algorithm01: 
```
baseScore = 1.01
print "This is promise:"
for i in range(8):
	baseScore *= baseScore
	print  "%d days inisit: %0.2f things" % (i+1,baseScore-1)
	
```

Finally, you will get a promise form me to complete N things.The number of N is the finnal score of this simple algorithm.

## Punishment Rule

baseScore = 1.03

Algorithm02: 

```
baseScore = 1.03
for i in range(6):
	baseScore *= baseScore
	print "%d days miss: %0.2f things" % (i+1,baseScore)

```

## Q&A  

### What I should do?

1. Write passed code.
2. Keep your code easy to read. Keep it as simple as you can.
3. Add some necessary comments to code
4. Write a note of question which contains your thought or roadmap if you have no idea of it

### Where I submit my code and notes?

1. Create a folder named [num]-[question_name] of this repo (ex. 001-linear_algorithm).
2. Submit anything to folder and push.

