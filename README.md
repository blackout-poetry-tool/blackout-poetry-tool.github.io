# Blackout Poetry Tool
## In the context of Human-Computer Dichotomy
**Dichotomy**
> A division or contrast between two things that are or are represented as being opposed.

A dichotomic lens on the Human-Computer relationship can look towards- 
- Intuition vs Logic, Quality vs Quantity, Emotional vs Mechanical

#

**Whenever there's a conflict between two entities, Peter Elbow [[1]](https://www.semanticscholar.org/paper/The-Uses-of-Binary-Thinking-Elbow/294d77e512c3eff76b5ddd105277ae489b07cdac) mentions 5 ways of resolving it -**
1. Choosing a better side.
2. Work out a synthesis (a middle ground).
3. Affirm both sides as true.
4. Add more than 2 sides.
5. Deny the presence of conflict.

**This project borrows these methods and translates them into modes of interaction between the author and a bot -**
1. Choosing a better side.
   - Thesis
     - Only the human performs
   - Antithesis
     - Only the bot performs
2. Work out a synthesis (a middle ground).
   - Synthesis
     - Human selects a word, then the bot selects a word.
3. Affirm both sides as true.
   - Symbiosis [[2]](http://groups.csail.mit.edu/medg/people/psz/Licklider.html)
     - Human selects a word, then the bot suggests the next.
4. Add more than 2 sides.
   - Visual
     - A new bot draws a wave- following visual rules over grammatical rules.
5. Deny the presence of conflict.
   - `As this mode proposes a counter-argument to human-computer dichotomy, I felt this should be addressed separately in the future.`
   
#

##### How does the bot write poetry?
This work employs two ways of achieving bot poetry (using library RiTa.js [[3]](https://rednoise.org/rita/)) - 
1. By matching a pre-set grammar-sequence:
   - Grammar Maker [[4]](https://blackout-poetry-tool.github.io/grammar-maker/), a mini-program was developed to identify a poet's most-frequently used grammar-sequence.
2. By detecting a selected word's grammar rule:
   - A markov-based n-gram model refers to Robert Frost's poetry corpus [[5]](http://www.gutenberg.org/files/59824/59824-h/59824-h.htm), and selects the next most-probable word.
  
#

##### Credits
This project was undertaken by [Jazer Chand](https://www.instagram.com/jazer.chand/), mentored by [Saumya Kharbanda](https://www.linkedin.com/in/saumyakharbanda) and [Dinesh Abiram](https://dineshabiram.wixsite.com/photography).

A huge shout-out to [Daniel Shiffman](https://shiffman.net/) and his wonderful creative-coding channel [Coding Train](https://www.youtube.com/user/shiffman/featured).

© 2021. This work is licensed under a [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).
