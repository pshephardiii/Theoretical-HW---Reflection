# Theoretical-HW---Reflection

* Week 1 Fizzbuzz *
No problems here.  The only difference is that I didn't put a parameter in the function defition, but rather set the required number in the for loop.  However, I understand that using the 'n' parameter there would help make the function more flexible.

* Week 2 Print Alphabet *
This wasn't a problem either, but I did it in an inefficient manner.  In the antecedent of my conditional, I used a lengthy disjunction to check for vowels rather than the .includes prototype.  I also put the alphabet array in the global space, which I should avoid if possible.

* Week 5 MaxChar *
This one was trickier and I did it quite a bit different from the suggested solution.  Instead of comparing each value with a for in loop, I used Math.max(...frequency) to assign a variable to the value with the highest frequency in the string.  It's not clear to me which approach is more efficient, though.

* Week 6 Find Anagrams *
By far the hardest theoretical hw for me to complete. I got it to work, but my code was very inefficient.  I think what I missed was the ability to assign a value to an object key as an array (fc[sortedWord = [word]]) and check if a key is in an object.  I think I had a difficult time thinking about object values as an array of arrays.  I also need to get more comfortable with bracket notation when it comes to messing with frequency counters.

* Week 7 Char Count *
Easy one here, and our solutions are similar except I made us of the replace prototype to remove the spaces.

* Week 8 reverseSentence *
I actually think my solution was more efficient than the suggested one!  The key for me was using the split and join prototypes with a space (' ') to retain spaces after reversing the order of words.  That being said, the proposed solution just does that manually with a confusing conditional, but as of now I see no reason to not use my own approach instead.
