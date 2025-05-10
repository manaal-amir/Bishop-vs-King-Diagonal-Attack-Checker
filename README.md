# Bishop vs King – Diagonal Attack Checker

This Python script checks if a bishop (`B`) can attack a king (`K`) on an 8x8 chessboard based on user input. It simulates bishop movements along diagonals and displays the board with possible attack paths.

---

## Input Format

- Enter the board as a **single string**, where:
  - Rows are separated by **semicolons (`;`)**
  - Cells in each row are separated by **commas (`,`)**
  - Use:
    - `"B"` for **bishop**
    - `"K"` for **king**
    - `"@"` or other characters for empty spots

### Example:  
@,@,@,@,@,@,@,@;@,@,@,@,B,@,@,@;@,@,@,@,@,@,@,@;@,@,@,@,@,@,@,@;@,@,@,@,@,@,@,@;@,@,@,@,@,@,@,@;@,@,@,@,@,@,@,@;@,@,K,@,@,@,@,@  


---

## How It Works

1. Prompts the user until a valid input with both `B` and `K` is entered.
2. Builds a 2D board from the input.
3. Simulates the bishop’s diagonal moves.
4. Marks reachable positions with `+`.
5. Displays the board and shows whether the king is under attack.

---

## Output

The board is printed in a grid format with `+` showing possible bishop moves. A message indicates if the king is in danger.  
![image](https://github.com/user-attachments/assets/e8e8e56c-d1eb-4ad4-b5dc-d888796735e4)


