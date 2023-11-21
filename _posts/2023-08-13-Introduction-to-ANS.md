---
layout: post	
title: "Introduction to ANS"
subtitle: "A modern approach to entropy coding."
background: '/img/posts/01.jpg'	
---

# Work in Progress
I came in contact with Asymmetric Numeral Systems first one year ago, when i looked deeper into entropy coding. Whilst stumbling over huffman coders and arithmetic coding, i crossed roads with ANS. At first glance it is surprising, how with those two old coders, which basicly solved entropy coding, such a new development took place. Delving deeper into all those coders, it becomes easy to notice the shortcomings of the two old coders and the elegance of ANS. The industry supports this view, by including ANS  in Zstandard, LZFSE, CRAM and many more. Unterstanding ANS at its full took me quite a while (and propably i am still not done with the process). So let me take you along the journey i took and hopefully make unterstanding ANS a little easier.

#  Some prerequisites