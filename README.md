# Algorithms for Decision Making
*Mykel Kochenderfer, Tim Wheeler, and Kyle Wray*

This book provides a broad introduction to algorithms for decision making under uncertainty. We cover a wide variety of topics related to decision making, introducing the underlying mathematical problem formulations and the algorithms for solving them.

Please file issues for suggestions and comments (or email the address listed at the bottom of the pages of the PDF).

We are interested in all forms of feedback including, but not limited to:
1. Errors
2. Improvements to code (especially improvements for clarity over speed)
3. Typos
4. Areas that are confusing
5. Critical topics that are missing
6. Ideas for examples or exercises

Book webpage: https://algorithmsbook.com

## Errata

### First printing

* [p. 99] Sec 5.2: In the first paragraph, change 2.4 to 2.3 (thanks to Dylan Asmar)
* [p. 108] Ex 5.4: Make edge E->D in the PDAG directed (thanks to Nikhil Raghuraman)
* [p. 121] Alg 6.2: Caption updated to reflect that algorithm returns the value of information (thanks to Griffin Holt) 
* [p. 157] Ex 7.9: Change solution to "then both policies are optimal" (thanks to Liam Kruse)
* [p. 174] Fig 8.13: Changed "polynomial" to "quadratic" (thanks to Balduin)
* [p. 192] Ex 9.5: Change N(s0) to 1, as count is not incremented until after exploration (thanks to Paul Diederichs)
* [p. 196] Ex 9.8: Change line plot colors to improve readability wrt color blindness (thanks to Zhen Wu)
* [p. 199] Alg 9.9: P.S should be prepended with "π." (thanks to Griffin Holt)
* [p. 226] Fix intermediate derivation in equation in solution of Ex 10.1 (thanks to Paul Diederichs)
* [p. 207] Ex 9.11, for consistency, change the Gaussian to have N(s' | ...)
* [p. 232] Alg 11.1: Added a note to indicate that the final state is not included in this data structure, as it is not needed in the ensuing algorithms (thanks to Joshua Ott) 
* [p. 246] Ex 11.2 solution: "theh" should be "the" (thanks to Marc Schlicting)
* [p. 265] Ex 12.3 Solution, first equation: change 0.3/0.3 to 0.3/0.2 (thanks to Asakura publishing)
* [p. 269] Alg 13.1 caption, change ∇θ to ∇Uθ and ∇θ to ∇ℓϕ (thanks to Asakura publishing)
* [p. 274] Alg 13.3 caption, change ∇θ to ∇Uθ and ∇θ to ∇ℓϕ (thanks to Asakura publishing)
* [p. 276] Note 6, 14th line: Change "Alpha Zero" to "AlphaGo Zero" (thanks to Asakura publishing)
* [p. 278] Ex 13.2 (c)-(h): All instances of `l` should be `\ell` (thanks to Asakura publishing)
* [p. 304] Ex 15.2 pinned the RNG to produce the output expected in the example description (thanks to Appoorva Dixit)
* [p. 304] Ex 15.2 changed the model creation code to `model = BanditModel(fill(Beta(), 2))`
* [p. 307] Ex 15.3 curve was not plotted with the correct demoninator, causing the curve to be too low (thanks to Hugo Buurmeijer)
* [p. 314] Ex 15.7 values for arm 1 were fixed (thanks to Mykel)
* [p. 317] Mention that when N(s,a) = 0, we can use a uniform distribution or set T(s,a) to zero (thanks to Mykel and Dylan Asmar)
* [p. 329] Eq 16.8: b in second P(s'|s,b,a) should be theta (thanks to Griffin Holt)
* [p. 330] Change the reference to Chapter 16 to be to Part 4 instead (thanks to Michael Sheehan)
* [p. 382] Ex 19.2: change from "perfect observation" to "a more accurate observation" (thanks to Kathryn Lesh)
* [p. 405] Ex 19.17 Solution, last equation: All instances of `\sigma _{p}` should be bold (thanks to Asakura publishing)
* [p. 414] Ex 20.2: 3rd line: Bolding the 'b' in `b = [0.5,0.5]` (thanks to Asakura publishing)
* [p. 436] Update Sec. 21.6 and implementation of utility() in Alg. 21.9 (thanks to Shengtong Zhang)
* [p. 461] Ex 22.5: change O(o2 | a3, s2) to O(o2 | a3, s1) (thanks to Dylan Asmar)
* [p. 467] Ex 22.1 Solution, first equation:  `P (o | b, a)` should have a bold `b` (thanks to Asakura publishing)
* [p. 468] Prob 22.3: update to reflect use of successor state in observation func (thanks to Dylan Asmar)
* [p. 468] Ex 22.2 Solution: In the last column of the table's header row,  "o" should be "o_a" (thanks to Asakura publishing)
* [p. 479] Alg 23.4: change comment "prune identical from previous nodes" to "prune identical from new nodes" (thanks to Emma Passmore)
* [p. 527] Table 27.1: change "Dec-POMDP" to "Dec-MDP" in caption (thanks to Dylan Asmar)
* [p. 585] Eq. D.6: change - to + (thanks to Jonathan Larkin)
* [p. 644] Sec. G.3.2: "x" in text should be "X" to be consistent with code (thanks to Ziyu Wang)
