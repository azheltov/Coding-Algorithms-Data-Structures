Scalability and Big O

// in JS we can use timers - let t0 = performace.now() - to measure the performnce and illustrate how many milliseconds certain task take
// Runtime matters
// Other factors: CPU power, other programs and etc.

What is good code?
1.Readable
2.Scalability

1. O(1) - Constant
(flat line)
example with boxes, we take just one box list[0] so input doesn't affect the result

2. O(n) - Liner time
number of operations depends on the input 
n - size of input

3. O(n^2) same as O(n * n)
nested loops

4 RULES of Big O

  Rule 1: Worst Case
("element in a list(input) can be the first or the last")

  Rule 2: Remove Constants
("it's important how the line formed, not the steepnes")

  Rule 3: Different terms for inputs                             |||||||| different inputs different variables

  Rule 4: Drop Non Dominants
("O(n + n^2) = O(n^2)")



