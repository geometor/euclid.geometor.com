---
title:  Proposition 11
subtitle:
author:
routes:
  aliases:
    - /elem.1.11
taxonomy:
  tag:
  category:
    -
---

To draw a straight line at right angles to a given straight line from a given point on it.


===

Let <em>AB</em> be the given straight line, and <em>C</em> the given point on it. <lb n="5"/>

Thus it is required to draw from the point <em>C</em> a straight line at right angles to the straight line <em>AB</em>.

Let a point <em>D</em> be taken at random on <em>AC</em>; <lb n="10"/>let <em>CE</em> be made equal to <em>CD</em>; [<a href="/elem.1.3">I. 3</a>] on <em>DE</em> let the equilateral triangle <em>FDE</em> be constructed, [<a href="/elem.1.1">I. 1</a>] and let <em>FC</em> be joined; 

I say that the straight line <em>FC</em> has been drawn at right <lb n="15"/>angles to the given straight line <em>AB</em> from <em>C</em> the given point on it.

For, since <em>DC</em> is equal to <em>CE</em>, and <em>CF</em> is common, <span class="center">the two sides <em>DC</em>, <em>CF</em> are equal to the two sides <em>EC</em>, <lb n="20"/><em>CF</em> respectively;</span> and the base <em>DF</em> is equal to the base <em>FE</em>; <span class="center">therefore the angle <em>DCF</em> is equal to the angle <em>ECF</em>; [<a href="/elem.1.8">I. 8</a>]</span> and they are adjacent angles.

But, when a straight line set up on a straight line makes <lb n="25"/>the adjacent angles equal to one another, each of the equal angles is right; [<a href="/elem.1.def.10">Def. 10</a>] <span class="center">therefore each of the angles <em>DCF</em>, <em>FCE</em> is right.</span>

Therefore the straight line <em>CF</em> has been drawn at right angles to the given straight line <em>AB</em> from the given point <lb n="30"/><em>C</em> on it.

<div class="QED">

Q. E. F.

</div>
[mermaid]
graph BT
classDef default fill:#CCC,stroke:#333,stroke-width:1px,cursor:pointer;
classDef prop fill:#FC3;
classDef def fill:#3CF;
classDef post fill:#C3F;
classDef cn fill:#CF3;

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

<blockquote n="10. let CE be made equal to CD." class="crit" place="unspecified" anchored="yes">

The verb is <foreign lang="greek">κείσθω</foreign> which, as well as the other parts of <foreign lang="greek">κεῖμαι</foreign>, is constantly used for the passive of <foreign lang="greek">τίθημι</foreign> <quote>to <em>place</em></quote>
; and the latter word is constantly used in the sense of <em>making</em>, e.g., one straight line equal to another straight line.

</blockquote>
