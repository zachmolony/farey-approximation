# Farey approximation
Finding rational approximation to irrational numbers using Farey sequencing in python.

### Farey Sequencing

A Farey sequence \[F(n)\] is a complete sequence of reduced form rational fractions in the range \[0...1]\ 

of the form \[F(n)={\begin{Bmatrix} \frac{0}{1}<\frac{a_{0}}{b_{0}}<.....\frac{a_{p}}{b_{p}}<\frac{1}{1}\ \end{Bmatrix}}\]

with b_{j}\leq n for \[\forall j\]. The sequence is complete in the sense that, given a Farey sequence as defined above, we can find no rational fraction \[frac{p}{q}\] with \[q\leq n\] such that \[\begin{matrix} \frac{a_{j}}{b_{j}}<\frac{p}{q}<\frac{a_{j+1}}{b_{j+1}} \end{matrix}\].
