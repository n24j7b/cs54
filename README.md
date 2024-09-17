java c
CS 3800              Spring 2024
Homework 4
1. [5 Points] Regular Operations. Let Σ = {a, b, c} and consider language A = {ca, b}. List the first twelve elements (in shortlex order) of A∗.
2. [13 Points] DFA construction. For each of the following languages over the alphabet {a, b}, draw the state transition diagram of a DFA with alphabet {a, b} that recognizes the language. For full credit, try to keep your solution simple (limit the number of states).
(a) ∅
(b) {ε}
(c) {ab, ba}
(d) {w | w starts with a and ends with b}
(e) {w | w has neither aa nor bb as substring}
(f) {w | there exist strings x and y such that w = xaabby}. That is, the language con-sists of those words that have the substring aabb.
3. [8 Points] DFA Complement. Let L = {w ∈ {a, b}* | the number of b’s in w isn’t 3}. For example ε, a, b, ababa, baabbab ∈ L but bbb, bababa ̸∈ L.
(a) Give the state diagram of a DFA for the complement L of L.
(b) Apply the methods of Lecture 8a to give the state diagram of a DFA for L.
4. [9 Points] Product method. Let Σ = {a, b, c} and consider languages {a, b}* and {a, c}*.
(a) Draw the state diagrams of finite automata M1 and M2 with alphabet Σ such that
L(M1) = {a, b}* and L(M2) = {a, c}*
To facilitate the following part (b), give distinct names to the states of your au-tomata.
(b) Apply the product construction of lecture 8a to draw the state diagram of a finite automaton M with
L(M) = L(M1) ∪ L(M2) = {a, b}* ∪ {a, c}*
5. [5 Points] NFAs acceptance Which, if any, of the strings below are accepted by the following nondeterministic finite automaton?

(a) aa
(b) aba
(c) ab
(d) aaab
(e) abab
代 写CS 3800 Spring 2024 Homework 4SPSS
代做程序编程语言6. [5 Points] NFAs. Let Σ = {a, b} and let
L = {w ∈ Σ* | w contains at least two a’s with exactly 6 characters between them}
For example, aabbababbabab ∈ L because there are exactly 6 characters between the third and the last a but ababbabbab ̸∈ L. Draw the state-diagram of a NFA that accepts L.
7. [10 Points] NFAs. Let Σ = {a, b, c, d} and let
L = {w ∈ Σ* | w ≠ ε and the last character of w appears nowhere else in w}
Draw the state-diagram of a NFA that accepts L.
8. [10 Points] Tint. (Submission is separate from the other problems. Instructions will be posted on Piazza.) Let Σ = {0, 1, 2} and consider the language
L ⊆ Σ*
that consists of all base-3 numerals that are divisible by 7. For example, 01022 ∈ L as 0 · 34 + 1 · 33 + 0 · 32 + 2 · 31 + 2 · 30 = 35 is divisible by 7.
Similarly, 00021, 00021210, , 10010 ∈ L but 02201, 10001 ̸∈ L
Note also, that ε ̸∈ L as the empty word isn’t a numeral .
Design and submit a deterministic finite automaton M such that L(M) = L.
9. [5 Points]. Tint. (Submission is separate from the other problems. Instructions will be posted on Piazza.) Let

A string of symbols from Σ defines two rows of 0s and 1s. Consider each row to be a binary number and let
D = {w ∈ Σ+ | the top row of w is a smaller number than the bottom row}
For example,  ∈ D because, as binary numbers, 0011 < 0100.
Construct a finite automaton that accepts D. Note that, due to the linearity of sym-bols in tint, the columns above have to be represented by strings of length 2. That is, Σ = {00, 01, 10, 11}. And “00 01 10 10” ∈ D because, as binary numbers, 0011 < 0100.





         
加QQ：99515681  WX：codinghelp
