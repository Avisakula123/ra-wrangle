# ra-wrangle
- The play I selected is The Tragedy of Hamlet, Prince of Denmark.
- My speaker 1 is Marcellus.
- My speaker 2 is Bernardo.
- The question is "Which speaker is repeated more in play?".
## Commands
- curl "http://shakespeare.mit.edu/hamlet/full.html" -O rrplay.txt
- $ grep -i 'MARCELLUS' rrplay.txt -c
- $ grep -i 'BERNARDO' rrplay.txt -c

## Speaker whose name repeated more.
- The answer is Marcellus.
