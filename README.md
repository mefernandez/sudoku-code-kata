sudoku-code-kata
================

Background on this kata
-----------------------

I'm really fond of code katas to practice Test Driven Development. You can find many on internet. They range from very simple problems to some more puzzling.

I confess I was a bit skeptical the first time I was introduced to TDD. I was under the impression the code katas were just to simple. I kept asking myself "would this work in the real world"? So I challenged myself to think about a problem and tried to find a solution with a TDD approach.

Sudokus were very popular by then. They were on the last page of every free newspaper. I though it was the perfect problem to give it a try on TDD. The requirements are plain simple, and almost everybody knows Sudokus' rules. However, I never tackled the problem from a programming point if view.

I first started looking for someone that had already given it a try with a TDD approach. I found an article at InfoQ.com discussing two approaches, one of them by Ron Jeffries.
http://www.infoq.com/news/2007/05/tdd-sudoku

Mr. Jeffries solution is exposed as a log of every step and decision taken. So I decided to give it a try myself and see what happens.

I want to thank Carlos Blé Jurado for introducing me to TDD, and by the way, take a look at his online book on TDD at: http://www.dirigidoportests.com/el-libro. It fetures a nice Calculator example evolving from scratch using TDD.

How this kata is structured
---------------------------

The first part of this document is straight a simple: simply put, it says "write a program that solves a Sudoku, and do it TDD".

The following sections propose one way to do it, putting some emphasis on the ways of seeing parts of the problem and not too much on code.

My suggestion is read the first iteration and "fly solo" from there.

Hopefully, there will be some nice conclusions at the end of this document.

First: Kata objetives
---------------------

In few words: Write a program that solves a Sudoku. Write it the TDD way.

You can find an online Sudoku generator here.
http://www.sudoku-online.org/

Second: Just looking at it
--------------------------

I honestly say I thought I couldn't do it. I had a hard time going through Mr. Jeffries article (my fault). So, how would I dare write such a program in this new mindset that is TDD? Too much.

I had to make a choice: either do some basic TDD or solve a problem that looked too big. 