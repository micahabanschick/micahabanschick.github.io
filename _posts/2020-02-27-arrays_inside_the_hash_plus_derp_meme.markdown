---
layout: post
title:      "Arrays inside the Hash (plus "derp" meme)"
date:       2020-02-27 16:35:17 -0500
permalink:  arrays_inside_the_hash_plus_derp_meme
---

For the most part I find arrays to be fairly simple. They contain multiple elements that represent a single objective (usually expressed by its variable name), and simplify that larger objective by containing it inside a variable. 
Kind of how we all learned that: 
```
5 x 10 = 50 === 5 + 5 + 5 + 5 + 5 + 5 + 5 + 5 + 5 + 5 = 50
```
Instead of mentally racing through the numbers, all we have to do is remember that multiplying by 10 requires nothing more than a zero being placed as the right-most digit. However, keeping track of multiple placeholders becomes more complicated as dimentions of code stack ontop of each other. And especially inside a hash, since the the retrieving of a piece of code in each is so similar (but still different).

```
hash = {
 one: [1,2,3,4],
 two: {arr: ["e1","e2","e3"],
       arr2: ["e4","e5","e6"]},
 three: "simple"
}
```
```
How do I reach "e6"?
It is hash [two][arr2][2]?
Or hash [two[arr2[2]]]?
Or hash [two][arr2][e6]?
Or hash [2][arr2][two]?
Or maybe something else?

```

It can become confusing when nesting inside multiple layers of hash and array. Where do you use the number 2 and where do you use the variable two? Although when isolated these problems are simple to fix, when stacked all together it can feel like decoding the Rosetta Stone. 

And for the sake of maintaining my self-proclaimed reputation I will end with an anime meme:

![](https://i.imgflip.com/3qiepf.jpg)


Thank you and good bye.

