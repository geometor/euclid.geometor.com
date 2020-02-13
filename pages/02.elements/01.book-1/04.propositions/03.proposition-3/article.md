---
title:  Proposition 3
subtitle: Construct equal segments by section
author:
routes:
  aliases:
    - /elem.1.3
taxonomy:
  tag:
    - proposition
    - construction
  category:
    - lines
---

Given two unequal straight lines, to cut off from the greater a straight line equal to the less.


===

Let `AB`, `C` be the-two given unequal straight lines, and let `AB` be the greater of them.

Thus it is required to cut off from `AB` the greater a straight line equal to `C` the less.

At the point `A` let `AD` be placed equal to the straight line `C`; [1.2] and with centre `A` and distance `AD` let the circle `DEF` be described. [1.post.3] 

Now, since the point `A` is the centre of the circle `DEF`, `AE` is equal to `AD`. [1.def.15] But `C` is also equal to `AD`. 
- Therefore each of the straight lines `AE`, `C` is equal to `AD`; so that `AE` is also equal to `C`. [1.c.n.1]

Therefore, given the two straight lines `AB`, `C`, from `AB` the greater `AE` has been cut off equal to `C` the less.

- (Being) what it was required to do.

## References

[1.def.15]: /elem.1.def.15 "Book 1 - Definition 15"
[1.2]: /elem.1.2 "Book 1 - Proposition 2"
[1.post.3]: /elem.1.post.3 "Book 1 - Postulate 3"
[1.c.n.1]: /elem.1.c.n.1 "Book 1 - Common Notion 1"


[mermaid]
graph BT

e1_3[1.3]
class e1_3 prop;
click e1_3 "/elem.1.3" "Book 1 Proposition 3";

%%%% dependencies

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
