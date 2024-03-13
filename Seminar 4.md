## Exerciții temă:
- ④ A: rezistență bună la șoc. B: rezistență bună la zgârieturi
$$\begin{aligned}P\left( A\right) =\dfrac{86}{100}=0,86,\\
P\left( B\right) =\dfrac{79}{100}=0,79,\\
P\left( A|B\right) =\dfrac{P\left( A\cap B\right) }{P\left( B\right) }=\dfrac{70}{79},\\
P\left( B|A\right) =\dfrac{P\left( B\cap A\right) }{P\left( A\right) }=\dfrac{70}{86},\\
P\left( B\cap A\right) =\dfrac{70}{75},\left( 1\right) ,\\
P\left( B\right) \cdot P\left( A\right) =\dfrac{86}{100}\times \dfrac{79}{100},\left( 2\right) ,\\
\left( 1\right) ,\left( 2\right) \Rightarrow P\left( B\cap A\right) \neq P\left( B\right) \times P\left( A\right) \end{aligned}$$
- ⑤ lot 100 produse, 5 au defecțiuni
$$P\left( \overline{A}_{1}\cap \overline{A}_{2}\cap \overline{A}_{3}\right) =P\left( \overline{A}_{l}\right) \times P\left( \overline{A_{2}}|\overline{A}_{1}\right) \times P\left( \overline{A_{3}}|\overline{A_{1}}\cap A_{2}\right) =\dfrac{95}{100}\times \dfrac{94}{99}\times \dfrac{93}{98}$$

- ⑥
$$\begin{aligned}P\left( A|B\right) =0,4,\\
P\left( B\right) =0,5,\\
P\left( A|B\right) =\dfrac{P\left( A\cap B\right) }{P\left( B\right) },\\
\Rightarrow P\left( A\cap B\right) =P\left( A|B\right) \times P\left( B\right) =0,2,\\
P\left( CA|B\right) =1-0,4=0,6,\\
P\left( CA\cap B\right) =P\left( B\right) \times P\left( CA|B\right) =0,5\times 0,6=0,3\end{aligned}$$
- ⑦ A și B = evenimente
$$\begin{aligned}P\left( A|B\right) =0,2,\\
P\left( B\right) =0,8,\\
P\left( A|CB\right) =0,3,\\
P\left( A\right) =?,\\
P\left( CB\right) =1-P\left( B\right) =1-0,8=0,2,\\
P\left( A\right) =P\left( A|B\right) \times P\left( B\right) +P\left( A|CB\right) \times P\left( CB\right) =0,2\times 0,8+0,3\times 0,2=0,22\end{aligned}$$

- ⑨ 5 întrebări, 3 răspunsuri
- a) A = eveniment exact un răspuns corect
$$P\left( A\right) =5\times \dfrac{1}{3}\times \left( \dfrac{2}{3}\right) ^{4}=\dfrac{5}{3}\times \dfrac{16}{81}=\dfrac{80}{243}$$

- b) P (cel puțin unul) = 1- P (niciunul)
$$\begin{aligned}P\left( c\right) =1-P\left( n\right) ,\\
P\left( n\right) =\left( \dfrac{2}{3}\right) ^{5},\\
\Rightarrow P\left( c\right) =1-\left( \dfrac{2}{3}\right) ^{5}=\dfrac{211}{243}\end{aligned}$$
- c) P (niciunul) = calculat la pct. anterior
- d) P (cel mult unul) = a) + c)

- ⑩ A, B = evenimente independente
$$\begin{aligned}P\left( A\right) =0,3,P\left( B\right) =0,4,\\
P\left( A\cap B\right) =P\left( A\right) \times P\left( B\right) =0,3\times 0,4=0,12,\\
P\left( A\cup B\right) =P\left( A\right) +P\left( B\right) -P\left( A\cap B\right) =0,58,\\
P\left( A\backslash B\right) =P\left( A\right) -P\left( A|B\right) =0,3-0,12=0,18\end{aligned}$$
## Exerciții seminarul 4(Formula lui Bayes)
- ① H1 = are boala. H 2 = nu are boala (H 1 negat) A + = test pozitiv. A - = test negativ
$$\begin{aligned}P\left( H_{1}\right) =\dfrac{2}{1000},\\
P\left( H_{2}\right) =\dfrac{998}{1000},\\
P\left( A+|H_{1}\right) =0,97,\\
P\left( A-|H_{2}\right) =0,95,\\
P\left( A+|H_{2}\right) =0,05,\\
P\left( H_{1}|A_{+}\right) =\dfrac{P\left( A+|H_{1}\right) \times P\left( H_{1}\right) }{P\left( A_{+}\right) },\\
P\left( A_{+}\right) =P\left( A_{+}|H_{1}\right) \times P\left( H_{1}\right) +P\left( A_{+}|H_{2}\right) \times P\left( H_{2}\right) =0,97\times 0,02+0,05\\
\times 0,998=0,051,\\
P\left( H_{1}|A_{+}\right) =\dfrac{0,97\times 0,002}{0,051}=0,038\end{aligned}$$

- ② 5 răspunsuri, 1 corect. 65% știe , 35% nu știe
- a) P (răspuns greșit la o întrebare)
$$\begin{aligned}P\left( H_{1}\right) =0,65,P\left( H_{2}\right) =0,35,\\
P\left( A\right) =P\left( H_{1}\right) \times P\left( A|H1\right) +P\left( H_{2}\right) \times P\left( A|H_{2}\right) =0,65\times 0+0,35\times 0,8\\
=0,28\end{aligned}$$

- b) P (răspuns corect, ghicit)
$$P\left( H_{2}|\overline{A}\right) =\dfrac{P\left( H_{2}\right) \times P\left( \overline{A}|H_{2}\right) }{P\left( \overline{A}\right) }=\dfrac{P\left( H_{2}\right) \times \left( 1-P\left( A|H_{2}\right) \right) }{1-P\left( A\right) }=\dfrac{0,35\times \left( 1-0,8\right) }{1-0,28}$$