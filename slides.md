---
theme: none
layout: cover
company: Takayasu Nasu
date: 21.04.2022
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

<v-clicks>

A binary number is a number expressed in the base-2 integer system, a method of mathematical expression which uses only two symbols: typically "0" (zero) and "1" (one).

</v-clicks>


---
layout: section-1
---

## Comparison Chart

|   |   |   |   |   |  |
|---|---|---|---|---| - |
| decimal | 0 | 1 | 2 | 3 | 4 |
| binary | 0000 | 0001 | 0010 | 0011 | 0100 |
|   |   |   |   |   |  |
| decimal | 5 | 6 | 7 | 8 | 9 |
| binary | 0101 | 0110 | 0111 | 1000 | 1001 |
|   |   |   |   |   |  |
| decimal | 10 | 11 | 12 | 13 | 14 |
| binary | 1010 | 1011 | 1100 | 1101 | 1110 |

---
layout: section-2
---

# Let's try the Quiz!

I'm going to quiz you guys now.

<v-click>

Solution of the quiz can be used binary logic.

I think a person who can solve this quiz less than five minutes is very talented.

</v-click>


<v-click>

## Are you guys ready?

</v-click>


---
layout: section-2
---

<v-click>

## There are 1,000 bottles of wine. Only one out of a 1,000 bottles of wine has a poison.

</v-click>

<v-click>

## You can make some slaves drink these bottles.

</v-click>

<v-click>

## You should find the poisoned bottle by the end of the 24 hours.

</v-click>

<v-click>

## How many slaves do you need?

</v-click>

---
layout: image-side
image: 'https://i.pinimg.com/originals/19/62/8a/19628ab3ab0b3e97812dcc4a66613cf4.jpg'
---

<style>
.slidev-layout.image.slidev-page-7 .image-contaier img {
  object-fit: contain;
}
</style>

# Clue 1

<v-click>

Not 1,000 slaves.

</v-click>

<v-click>

# Clue 2

</v-click>

<v-click>

You should try to think case of only two bottles first.

</v-click>

<v-click>

# Clue 3

</v-click>

<v-click>

You should try to think case of four bottles next.

</v-click>

---
layout: image-side
image: 'https://i.pinimg.com/originals/01/35/4e/01354eb5a6becf5ec0ff05a6506dae6d.jpg'
---

<style>
.slidev-layout.image.slidev-page-8 .image-contaier {
  height: 28em;
}
.slidev-page-8 img {
  object-fit: contain !important;
}
</style>

# Special clue

<br>

<v-click>

## It is different number of bottles that slaves have to drink.<br>There is a case which nobody die.

</v-click>

<style>
.slidev-page-8 h2 {
  font-size: 40px;
}
</style>

---
layout: section-1
---

# Do you find a solution? <br> Do you need more thinking thime? <br> Next slide is showen anser.

---
layout: section-1
---

# Answer

<v-click>

# 10 slaves

</v-click>

---
layout: content-1
---

# End

<v-click>

![Remote Image](https://i.pinimg.com/originals/36/ef/2a/36ef2a8341ec788b4601d13b130683fc.jpg)

Tell me how to solve it!!

</v-click>


<style>
.slidev-page-11 p {
  text-align: center;
}
.slidev-page-11 img {
  margin: 0 auto;
  object-fit: contain;
  height: 16em;
}
</style>

---
layout: image-side
image: 'https://miro.medium.com/max/1838/1*ypQIMZY3QWc51ciNfhLlmg.png'
---

## Solution

<v-clicks>

- If there is only one wine bottle, you need one slave.
- If there are two wine bottles, you need one slave and you can find one the slave is gonna die or not.
- If there are three wine, you need two slaves.
- The first slave will drink 1, the second slave will drink 2, and if they both don't die, you'll know it's 3.
- If there are four wine, you need two slaves.
- If there are five wine, you need three slaves.

</v-clicks>

---
layout: content-1
---

# Case of two slaves

> '1' is drink, '0' is not drink.


| wine / slave  |   s1  |  s2   |
| --- | --- | --- |
|  w1  |  0  |  0  |
|  w2  |  0  |  1  |
|  w3  |  1  |  0  |
|  w4  |  1  |  1  |

<v-clicks>

- If slave 1 died, which bottle does have poison?
- w3 has poison.

</v-clicks>

---
layout: content-2
---

| wine / slave  |   s1  |  s2   | s3 |
| --- | --- | --- | -- |
|  w1  |  0  |  0  | 0 |
|  w2  |  0  |  0  | 1 |
|  w3  |  0  |  1  | 0 |
|  w4  |  0  |  1  | 1 |
|  w5  |  1  |  0  | 0 |
|  w6  |  1  |  0  | 1 |
|  w7  |  1  |  1  | 0 |
|  w8  |  1  |  1  | 1 |


---
layout: section-1
---

## Comparison Chart

|   |   |   |   |   |  |
|---|---|---|---|---| - |
| decimal | 0 | 1 | 2 | 3 | 4 |
| binary | 0000 | 0001 | 0010 | 0011 | 0100 |
|   |   |   |   |   |  |
| decimal | 5 | 6 | 7 | 8 | 9 |
| binary | 0101 | 0110 | 0111 | 1000 | 1001 |
|   |   |   |   |   |  |
| decimal | 10 | 11 | 12 | 13 | 14 |
| binary | 1010 | 1011 | 1100 | 1101 | 1110 |


---
layout: content-2
---

## Case of ten slaves


| wine / slave  |   s1  |  s2   | s3 | s4 | s5 | s6 | s7 | s8 | s9 | s10 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  w1  |  0  |  0  |  0  |  0  |  0  |  0  |  0  |  0  |  0  |  0  |
|  w2  |  0  |  0  |  0  |  0  |  0  |  0  |  0  |  0  |  0  |  1  |
|  w3  |  0  |  0  |  0  |  0  |  0  |  0  |  0  |  0  |  1  |  0  |
|  w4  |  0  |  0  |  0  |  0  |  0  |  0  |  0  |  0  |  1  |  1  |
|  w5  |  0  |  0  |  0  |  0  |  0  |  0  |  0  |  1  |  0  |  0  |
|  ...  |    |    |    |    |    |    |    |    |    |    |
|  w10  |  1  |  1  |  1  |  1  |  1  |  0  |  0  |  1  |  1  |  1  |

<v-click>

If nobody died, bottle 1 has poison.

</v-click>

<v-click>

If slaves 6 and 7 didn't die, bottle 10 has poison.

</v-click>


---
layout: section-2
---

##### For example, let's say there are 'x' slaves and 'y' bottles of wine to check.

```
y = 2^x
```

<v-click>

##### If there are 1,000 wine bottles,

```
1000 = 2^x
log(1000) = log(2^x) = x*log(2)
x = log(1000)/log(2) = 9.966
```

</v-click>

<v-click>

You need about 9.9 slaves, so totally you have to have 10 slaves if you wanna live.

</v-click>


---
layout: end
---

# Thank you for your time and attention!

[https://www.youtube.com/watch?v=TDh5XUJP0nc&t=1604s](https://www.youtube.com/watch?v=TDh5XUJP0nc&t=1604s)

