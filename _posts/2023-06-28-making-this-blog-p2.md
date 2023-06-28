---
layout: article
title: Making this blog - P2
mathjax: true
---

# Katex vs MathJax

So today I tried to implement Katex. Its an alternative to MathJax with the advantage that it doesn't take a stupidly long time to render and does not spill its gooey latex insides around while rendering. But Katex seems to have two problems

1. Some of its font doesn't match that of MathJax or Latex at all. Even in math mode all the characters feel like they have been written inside `\text{}`. It looks ugly and isn't ideal but I was ready to reach a compromise somehow but that wouldn't be possible because, 
2. Github, for some reason, doesn't exactly like Katex. I dont understand the technicality of how or why, but it just feels too complicated to add Katex support right now. I mean it is very tempting but then it also isn't an immediate necessity for the blog. It can wait. 

So in this round of *Katex vs MathJax*, MathJax wins. I'll come around to this problem later in the future. 

# What's Next

The terrible feeling that I'll have to finally dip my toe into actual Web Dev, and understand properly what I'm doing, just keeps growing day by day. Customising the blog on my own will require proper css and html knowledge that I don't posess right now. And while it'll be intersting to learn, I don't think I can learn at a pace where I can also implement what I'm learning at the same time. I say its a terrible feeling because its a far longer process than just installing some jekyll theme. But now that I have a site, I'll remain restless until I am actually satisfied with how it looks. So I have kind of cursed myself into learning web dev now. I look forward to finally understanding what all that css and html means inside those `_layout/` folders. 

As far as blog posts are concerned, I'll start writing some math-y ones soon. I have like one or two planned and I'm honestly not able to do as much math as I'd like now so I don't exactly have much interesting content at my disposal. But yeah parallely I'll keep looking at how I can embed more complicated Latex in here, mainly say tikz figures. But from what ever research I have done today, I'll probably have to settle with high quality images instead. We'll see, I'll find a way.  