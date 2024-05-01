1. The bug was that text was input by user as a string, so in calculateSum where there is the + operator it would perform string concatenation instead of arithmetic operations.
2. I would convert input values from strings to numbers so arithmetic operations were properly done. ![fix](https://raw.githubusercontent.com/karinnamonzon/sp24-cse110-lab4/main/explore/part2dev.PNG)
