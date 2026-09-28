# Origins of Math — Problem Set 1

**Due:** October 5, 2026

Show your reasoning and label any diagrams you use. A proof should explain why a statement holds in general; checking several examples is not enough. For historical questions, cite the sources and specific passages you use. Translations of ancient texts are welcome.

**Submission:** Submit the historical essay (Problem 3) and the GIMPS responses (Problem 5) as text documents. Submit the remaining work (Problems 1, 2, 4, and 6), including all diagrams, as a single PDF file. Do not submit snapshots or separate image files.

## 1. A proof of the Pythagorean theorem

Let ABC be a right triangle with right angle at C. Write BC = a, AC = b, and AB = c. Draw the altitude from C to the hypotenuse AB, and call its foot D. Write BD = c₁ and AD = c₂, so that c₁ + c₂ = c.

(a) Draw and label the figure. Identify the pairs of similar triangles and explain why they are similar.

(b) Use similarity to prove that

\[
\frac{a}{c}=\frac{c_1}{a}
\qquad\text{and}\qquad
\frac{b}{c}=\frac{c_2}{b}.
\]

(c) Clear the denominators and add the resulting equations. Deduce that

\[
a^2+b^2=c^2.
\]

*Adapted from Jay Cummings, Math History: A Long-Form Mathematics Textbook, Exercise 3.6.*

## 2. An angle in a semicircle

Thales’ theorem states that if AB is a diameter of a circle and P is any other point on the circle, then angle APB is a right angle. In this problem, you will construct a geometric proof. Treat the construction as a possible mathematical argument, rather than as evidence of the particular proof Thales used.

(a) Draw three rectangles with different proportions. Draw both diagonals of each rectangle. For each rectangle, explain why the circle centered at the intersection of the diagonals and passing through one vertex also passes through the other three vertices. Which segments are diameters of this circle?

(b) Use your drawings to develop a proof of Thales’ theorem. Explain why your argument applies to any point P on the semicircle, other than the endpoints of its diameter, rather than only to the rectangles you drew.

*Hint:* Draw the point opposite P on the circle and connect the four points. Use properties of diagonals to identify the resulting quadrilateral.

(c) In a short paragraph, explain how the drawing helped you discover the argument. What facts still needed to be justified to turn the picture into a proof?

*Adapted from Jay Cummings, Math History: A Long-Form Mathematics Textbook, Exercise 3.2.*

## 3. What can we learn about Thales from later authors?

Find one passage by Aristotle and one by Proclus that discuss Thales. Consult translations of the ancient works themselves wherever possible; you may use modern scholarship to help locate and interpret the passages.

Write approximately 400–600 words addressing the following questions:

(a) What does each author claim about Thales? Identify the work and the specific passage, and give the translator or edition you used.

(b) Approximately how long after Thales did each author write? What sources or earlier authorities, if any, does the author identify for the claim?

(c) How well supported is each claim? Consider the author's purpose, distance from the events, and the evidence offered. Distinguish what the passage explicitly says from what you infer.

(d) What is the difference between showing that a proof could have been available to Thales and showing that he actually used it? Relate your answer to Problem 2.

## 4. Parity in Pythagorean triples

A Pythagorean triple is a triple of positive integers (a, b, c) satisfying

\[
a^2+b^2=c^2.
\]

(a) Prove that the square of any integer leaves remainder 0 or 1 when divided by 4. You may begin by considering even and odd integers separately.

(b) Use part (a) to prove that a and b cannot both be odd.

**Optional challenge.** A Pythagorean triple is called primitive if a, b, and c have no common divisor greater than 1. Prove that in a primitive Pythagorean triple, exactly one of a and b is even and c is odd.

## 5. Mathematics in progress

In class, we studied Mersenne primes. Now investigate the Great Internet Mersenne Prime Search (GIMPS): <https://www.mersenne.org/>.

(a) In approximately 200–300 words, explain how GIMPS organizes a search across many computers and how participants’ computations contribute to the project. Describe the main stages at a level that a classmate could understand; you do not need to explain the technical details of the testing algorithms. Cite the pages you consult.

(b) Find the largest known prime currently reported by GIMPS. State it in exponential notation, give its discovery date, and record the date on which you checked the website.

**Optional participation.** If you have access to a suitable computer and permission to use it for this purpose, follow GIMPS’s instructions to participate. Participation is not required for credit. If your computer finds a new prime, let me know!

## 6. Triangular numbers and squares

Figurate numbers can be represented by geometric arrangements of dots. The nth triangular number is

\[
t_n=1+2+\cdots+n.
\]

Thus t₁ = 1, t₂ = 3, t₃ = 6, and t₄ = 10. In class, we gave a geometric proof that

\[
t_n=\frac{n(n+1)}2.
\]

(a) Given t₁₀₀₀ = 500500, calculate t₁₀₀₁ as simply as possible. Explain your method.

(b) Calculate t₁ + t₂, t₂ + t₃, and t₃ + t₄. What pattern do you notice? State a conjecture for tₙ + tₙ₊₁.

(c) Prove your conjecture geometrically by arranging two consecutive triangular arrays of dots into a familiar shape. Include a labeled drawing and explain why the construction works for every positive integer n.

(d) Prove the same identity algebraically using the formula for tₙ. Explain how the result corresponds to your geometric construction.

(e) Why do the three calculations in part (b) not, by themselves, prove your conjecture? What makes your argument in part (c) apply to every positive integer n?

(f) Calculate

\[
139+140+141+\cdots+296
\]

as efficiently as possible. Express the sum as a difference of triangular numbers and show your calculation.
