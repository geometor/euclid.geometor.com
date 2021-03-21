---
title:  Proposition 1.11
subtitle:
author:
routes:
aliases:
  - /elem.1.11
taxonomy:
    tag:
    category:
---

To draw a straight line at right angles to a given straight line from a given point on it.

===

Let `AB` be the given straight line, and `C` the given point on it. 

Thus it is required to draw from the point `C` a straight line at right angles to the straight line `AB`.

Let a point `D` be taken at random on `AC`; [^1] let `CE` be made equal to `CD`; [1.3] on `DE` let the equilateral triangle `FDE` be constructed, [1.1] and let `FC` be joined; 

I say that the straight line `FC` has been drawn at right angles to the given straight line `AB` from `C` the given point on it.

For, since `DC` is equal to `CE`, and `CF` is common, 

- the two sides `DC`, `CF` are equal to the two sides `EC`, `CF` respectively;

and the base `DF` is equal to the base `FE`; 

- therefore the angle `DCF` is equal to the angle `ECF`; [1.8]

 and they are adjacent angles.

But, when a straight line set up on a straight line makes the adjacent angles equal to one another, each of the equal angles is right; [1.def.10] 

- therefore each of the angles `DCF`, `FCE` is right.

Therefore the straight line `CF` has been drawn at right angles to the given straight line `AB` from the given point `C` on it.

- Q. E. F.

## References

[1.def.10]: /elem.1.def.10 "Book 1 - Definition 10"
[1.1]: /elem.1.1 "Book 1 - Proposition 1"
[1.3]: /elem.1.3 "Book 1 - Proposition 3"
[1.8]: /elem.1.8 "Book 1 - Proposition 8"


[mermaid]
graph BT

e1_11[1.11]
class e1_11 prop; 
click e1_11 "/elem.1.11" "Book 1 Proposition 11";

%%%% dependencies

e1_1[1.1]
class e1_1 prop; 
click e1_1 "/elem.1.1" "Book 1 Proposition 1";

e1_3[1.3]
class e1_3 prop; 
click e1_3 "/elem.1.3" "Book 1 Proposition 3";

e1_8[1.8]
class e1_8 def; 
click e1_8 "/elem.1.8" "Book 1 Proposition 8";

%%%% links

e1_11 --> e1_1
e1_11 --> e1_3
e1_11 --> e1_8


e1_3[1.3]
class e1_3 prop;
click e1_3 "/elem.1.3" "Book 1 Proposition 3";

%%%% e1_3 dependencies

e1_2[1.2]
class e1_2 prop;
click e1_2 "/elem.1.2" "Book 1 Proposition 2";

e1_post3(1.ax.3)
class e1_post3 post;
click e1_post3 "/elem.1.post.3" "Book 1 Postulate 3";

e1_def15(1.def.15)
class e1_def15 def;
click e1_def15 "/elem.1.def.15" "Book 1 Definition 15";

e1_cn1(1.cn.1)
class e1_cn1 cn;
click e1_cn1 "/elem.1.c.n.1" "Book 1 Common Notion 1";

%%%% links

e1_3 --> e1_2
e1_3 --> e1_post3
e1_3 --> e1_def15
e1_3 --> e1_cn1


[/mermaid]

## Footnotes 

[^1]: let CE be made equal to CD.
    The verb is <foreign lang="greek">κείσθω</foreign> which, as well as the other parts of <foreign lang="greek">κεῖμαι</foreign>, is constantly used for the passive of <foreign lang="greek">τίθημι</foreign> <quote>to <em>place</em></quote> ; and the latter word is constantly used in the sense of <em>making</em>, e.g., one straight line equal to another straight line.

