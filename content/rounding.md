---
title: Rounding
order: 3
---

Values can be rounded to a certain accuracy to create approximations.

When a value has been rounded, the resulting approximation may be shown with the number of decimal places or significant figures in brackets to show its accuracy and to communicate that it is an approximation.

By giving the number of decimal places or significant figures, you can work out the range of possible values for the exact value. For example,

$$
x = 0.2 \text{ (to 1 d.p.)}
$$

$$
0.15 \leq x < 0.25
$$

When performing calculations with rounded approximations, round the results to a suitable degree of accuracy. Results should not be more accurate than the values used to find them.

Chopping is another method of approximation where digits beyond a certain number of decimal places are dropped.

$$
\begin{array}{|c|c|}
\hline
x & x \text{ chopped to 1 d.p.} \\ \hline
8.76 & 8.7 \\ \hline
9.999 & 9.9 \\ \hline
1.01 & 1.0 \\ \hline
\end{array}
$$

When many approximations are made, there is often a cumulative effect to accuracy.

1000 random values with 1 decimal place are rounded to integers. The absolute error in each approximation will depend on the value of each tenth digit. The absolute error for each possible tenth digit is shown below:

$$
\begin{array}{|c|c|c|c|c|c|c|c|c|c|c|}
\hline
x & 0.0 & 0.1 & 0.2 & 0.3 & 0.4 & 0.5 & 0.6 & 0.7 & 0.8 & 0.9 \\ \hline
X & 0 & 0 & 0 & 0 & 0 & 1 & 1 & 1 & 1 & 1 \\ \hline
\text{Abs error} & 0.0 & -0.1 & -0.2 & -0.3 & -0.4 & +0.5 & +0.4 & +0.3 & +0.2 & +0.1 \\ \hline
\end{array}
$$

If each of the ten possible tenth digits are equally likely to appear on each of the 1000 values, the average absolute error will be the average of the above absolute error row which is 0.05. This will make the absolute error in the total approximately 50.

<figure class="image is-16by9"><iframe class="has-ratio" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRKd5ny-fNfDVyh9Q_1DYqyWum7mKw38cOTSk4dMZBVHT9G6I_V1IdZmR0914UZyez9djSZqyVUUifU/pubhtml?gid=0&single=true&widget=false&headers=false&chrome=false" scrolling="no"></iframe></figure>

If each of the 1000 random values with 1 decimal place are instead chopped to integers, the table will change.

$$
\begin{array}{|c|c|c|c|c|c|c|c|c|c|c|}
\hline
x & 0.0 & 0.1 & 0.2 & 0.3 & 0.4 & 0.5 & 0.6 & 0.7 & 0.8 & 0.9 \\ \hline
X & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 \\ \hline
\text{Abs error} & 0.0 & -0.1 & -0.2 & -0.3 & -0.4 & -0.5 & -0.6 & -0.7 & -0.8 & -0.9 \\ \hline
\end{array}
$$

Using the same method as above, the average absolute error can be found to be -0.45. The absolute error in the total will therefore be approximately -450.

<figure class="image is-16by9"><iframe class="has-ratio" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRKd5ny-fNfDVyh9Q_1DYqyWum7mKw38cOTSk4dMZBVHT9G6I_V1IdZmR0914UZyez9djSZqyVUUifU/pubhtml?gid=115923683&single=true&widget=false&headers=false&chrome=false" scrolling="no"></iframe></figure>
