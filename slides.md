---
theme: none
layout: cover
company: Takayasu Nasu
date: 30.11.2021
fonts:
  # like font-family in css, you can use `,` to separate multiple fonts for fallback
  sans: 'Fredericka+the+Great, cursive'
  serif: 'Fredericka+the+Great, cursive'
---

# Let's think briefly in terms of computer science together.

---
layout: content-1
---

# agenda


- Ice break
- Let's try the Quiz!
- Clue1
- Clue2
- Solution


---
layout: section-2
---

# Ice break

Have you hard word of "binary"?

A binary number is a number expressed in the base-2 integer system, a method of mathematical expression which uses only two symbols: typically "0" (zero) and "1" (one).


---
layout: section-2
---

# Let's try the Quiz!


I'm going to quiz you guys now.

Solution of the quiz can be used binary logic.

I think a person who can solve this quiz less than five minutes is very talented.

## Are you guys ready?



---
layout: section-2
---

## There are 1,000 bottles of wine. Only one out of a 1,000 bottles of wine has a poison.
## You can make some slaves drink these bottles.
## You should find the poisoned bottle by the end of the 24 hours.
## How many slaves do you need?

---
layout: section-1
---

# Clue 1 <br> Not 1,000 slaves.

---
layout: section-1
---

# Clue 2 <br> You should try to think case of only two bottles first.

---
layout: section-1
---

# Clue 3 <br> You should try to think case of four bottles next.

---
layout: section-1
---

# Special clue <br> Some slaves should drink more than one bottle, One slave has to drink only one bottle.

---
layout: section-1
---

# Do you find a solution? <br> Do you need more thinking thime? <br> Next slide is showen anser.

---
layout: section-1
---

# A. 10 slaves.

---
layout: image-side
image: 'https://miro.medium.com/max/1838/1*ypQIMZY3QWc51ciNfhLlmg.png'
---

## Solution

- If there is only one wine bottle, you need one slave.
- If there are two wine bottles, you need one slave and you can find one the slave is gonna die or not.
- If there are three wine, you need two slaves.
- The first slave will drink 1, the second slave will drink 2, and if they both don't die, you'll know it's 3.
- If there are four wine, you need two slaves.
- If there are five wine, you need three slaves.

---
layout: section-2
---

##### For example, let's say there are 'x' slaves and 'y' bottles of wine to check.

```
y = 2^x
```


##### If there are 1,000 wine bottles,

```
1000 = 2^x
log(1000) = log(2^x) = x*log(2)
x = log(1000)/log(2) = 9.966
```

You need 9.966 slaves, so totally you have to have 10 slaves if you wanna live.

[https://www.youtube.com/watch?v=TDh5XUJP0nc&t=1604s](https://www.youtube.com/watch?v=TDh5XUJP0nc&t=1604s)

---
layout: end
---

# Thank you for your time and attention!

