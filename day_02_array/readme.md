## linked list 

1. The Real-Life Analogy
Imagine you are on a scavenger hunt.

The Array (Yesterday): All the clues are written on a single sheet of paper in a list. You know exactly where Clue #5 is.

The Linked List (Today): You find a box. Inside is a Value (the clue) and a Note (a pointer) telling you the address of the next box. You have no idea where the 5th clue is until you visit Clue 1, then 2, then 3, then 4.

1. Why do we care in Data Science?
Arrays are great for looking things up, but terrible at adding or removing things in the middle (remember the mailbox shift?). Linked Lists are the opposite:

Adding/Deleting is fast: You just change where the "Note" points. You don't have to move any other boxes!

Access is slow: To find the 100th item, you have to walk through 99 items first.

1. The Anatomy of a "Node"
In Python, we don't have a built-in "Linked List" type like we do with Lists. We build it using a Class. Think of a Class as a blueprint for a single box (a Node).

Data: The actual info (like a temperature or a price).

Next: The link to the next box (or None if it's the end of the line).
