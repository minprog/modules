# Questions: Python

> Beantwoord de volgende vragen in je eigen woorden, in Nederlands of Engels.


## 1

Recall that, in lecture, we saw an implementation of a spell checker in Python.

Why were we able to implement a spell checker in Python using fewer lines of code than it took to implement a spell checker in C?

<textarea name="form[q1a]" rows="8" required></textarea>

Why did the spell checker in Python likely run slower than the spell checker you wrote in C?

<textarea name="form[q1a]" rows="8" required></textarea>


## 2

Recall from lecture that, whereas C programs are compiled, Python programs are interpreted. In your own words, what does it mean for a programming language to be interpreted language?

<textarea name="form[q2]" rows="8" required></textarea>


## 3

Recall that, in C, to get a positive integer between 1 and 8, inclusive, we could use code like the below.

	1  int n;
	2  do
	3  {
	4      n = get_int("Height: ");
	5  }
	6  while (n < 1 || n > 8);

In Python, there are no do while loops, so we would express the same idea as the below.

	1  while True:
	2  n = get_int("Height: ")
	3  if n >= 1 and n <= 8:
	4      break

Explain how these blocks of code are logically equivalent, as by explaining how each works line by line. 

<textarea name="form[q3]" rows="8" required></textarea>
