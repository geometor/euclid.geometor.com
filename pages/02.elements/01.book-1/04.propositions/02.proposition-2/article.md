---
title:  Proposition 2
subtitle: Construct equal segments by extension
author:
routes:
  aliases:
    - /elem.1.2
taxonomy:
  tag:
  category:
    - lines
---

To place at a given point (as an extremity) a straight line equal to a given straight line.

===

Let `A` be the given point, and `BC` the given straight line.

Thus it is required to place at the point `A` (as an extremity) <lb n="5"/>a straight line equal to the given straight line `BC`. 

From the point `A` to the point `B` let the straight line `AB` be joined; [<a href="/elem.1.post.1">Post. 1</a>] and on it let the equilateral triangle <lb n="10"/>`DAB` be constructed. [<a href="/elem.1.1">I. 1</a>]

Let the straight lines `AE`, `BF` be produced in a straight line with `DA`, `DB`; [<a href="/elem.1.post.2">Post. 2</a>] with centre `B` and distance `BC` let the <lb n="15"/>circle `CGH` be described; [<a href="/elem.1.post.3">Post. 3</a>] and again, with centre `D` and distance `DG` let the circle `GKL` be described. [<a href="/elem.1.post.3">Post. 3</a>]

Then, since the point `B` is the centre of the circle `CGH`, <span class="center">`BC` is equal to `BG`.</span>

<!-- <lb n="20"/> -->

Again, since the point `D` is the centre of the circle `GKL`, <span class="center">`DL` is equal to `DG`.</span>

And in these `DA` is equal to `DB`; <span class="center">therefore the remainder `AL` is equal to the remainder `BG`. [<a href="/elem.1.c.n.3">C.N. 3</a>]</span>

<!-- <lb n="25"/> -->

But `BC` was also proved equal to `BG`; <span class="center">therefore each of the straight lines `AL`, `BC` is equal to `BG`.</span>

And things which are equal to the same thing are also equal to one another; [<a href="/elem.1.c.n.1">C.N. 1</a>] <lb n="30"/><span class="center">therefore `AL` is also equal to `BC`.</span>

Therefore at the given point `A` the straight line `AL` is placed equal to the given straight line `BC`.

<div class="QED">

(Being) what it was required to do.

</div>

[mermaid]
graph BT
classDef default fill:#CCC,stroke:#333,stroke-width:1px,cursor:pointer;
classDef prop fill:#FC6;
classDef def fill:#6CF;
classDef post fill:#C6F;
classDef cn fill:#CF6;

e1_2[1.2]
class e1_2 prop; 
click e1_2 "/elem.1.2" "Book 1 Proposition 2";

%%%% dependencies

e1_1[1.1]
class e1_1 prop; 
click e1_1 "/elem.1.1" "Book 1 Proposition 1";

e1_post1(1.post.1)
class e1_post1 post;
click e1_post1 "/elem.1.post.1" "Book 1 Postulate 1";

e1_post2(1.post.2)
class e1_post2 post;
click e1_post2 "/elem.1.post.2" "Book 1 Postulate 2";

e1_post3(1.post.3)
class e1_post3 post;
click e1_post3 "/elem.1.post.3" "Book 1 Postulate 3";

e1_def15(1.def.15)
class e1_def15 def;
click e1_def15 "/elem.1.def.15" "Book 1 Definition 15";

%%%% links

e1_2 --> e1_1
e1_2 --> e1_post1
e1_2 --> e1_post2
e1_2 --> e1_post3
e1_2 --> e1_def15

[/mermaid]

<blockquote n="1. (as an extremity)." class="crit" place="unspecified" anchored="yes">

<p>I have inserted these words because <quote>to place a straight line <em>at</em> a given point</quote>
 (<foreign lang="greek">πρὸς τῷ δοθέντι σημείῳ</foreign>) is not quite clear enough, at least in English.</p>

</blockquote>
<blockquote n="11. Let the straight lines AE, BF be produced...." class="crit" place="unspecified" anchored="yes">

<p>It will be observed that in this first application of <a href="/elem.1.post.2">Postulate 2</a>, and again in <a href="/elem.1.5">I. 5</a>, Euclid speaks of the <em>continuation</em> of the straight line as that which is produced in such cases, <foreign lang="greek">ἐκβεβλήσθωσαν</foreign> and <foreign lang="greek">προσεκβεβλήσθωσαν</foreign> meaning little more than <em>drawing</em> straight lines <quote>in a straight line with</quote>
 the given straight lines. The first place in which Euclid uses phraseology exactly corresponding to ours when <pb n="245"/>speaking of a straight line being produced is in <a href="/elem.1.16">I. 16</a>: <quote>let one side of it, `BC`, be produced to `D`</quote>
 (<foreign lang="greek">προσεκβεβλήσθω αὐτοῦ μία πλευρὰ ἡ ΒΓ ἐπὶ τὸ Δ</foreign>).</p>

</blockquote>

<blockquote n="23. the remainder AL...the remainder BG." class="crit" place="unspecified" anchored="yes">

<p>The Greek expressions are <foreign lang="greek">λοιπὴ ἡ ΑΛ</foreign> and <foreign lang="greek">λοιπῇ τῇ</foreign> BH, and the literal translation would be <quote>`AL` (or `BG`) <em>remaining</em>,</quote>
 but the shade of meaning conveyed by the position of the definite article can hardly be expressed in English.</p>

</blockquote>
