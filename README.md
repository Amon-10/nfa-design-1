# NFA Design Assignment 1

## Problems Completed
I completed problems 6, 8, 12, 14, and 15.

## Most Challenging Problem
Problem 8 was the most challenging because it required thinking about nondeterministic branching to correctly handle both prefix and suffix conditions.

## Gold-St-Ring Experiences
In Problem 6, my machine initially rejected strings longer than "10" because I did not include self-loops on the accepting state. This helped me understand that acceptance only occurs after the entire input is processed.

In Problem 12, I had to carefully handle transitions after exactly three 1’s to avoid accidentally accepting a fourth 1.

## Lessons Learned
- NFAs can have missing transitions, but DFAs cannot.
- Acceptance does not mean the machine stops reading input.
- Testing shortest, typical, and corner-case strings is essential.
- Batch run helped me discover unexpected behaviors.

## Reflection
Designing NFAs helped me better understand nondeterminism and state transitions. The debugging process improved my understanding of how machines process input step-by-step.
