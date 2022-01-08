# Minesweeper-Matrix
Formative assesment - ICS4U

### Interpretation
Use recursive calls on each above, below, right, left, diagonals.

On the first pass you check all surrounding elements, on other calls you add value and check all surrounding ones if they are green.

If you are only supposed to check the element on the first pass like any other element, simply remove the check for ( || sum == 0) in if stament check ```main.c```.

### Parameters
 > Call a function to evaluate this cell in the grid
 > Firstly set the cell to OPEN (open the cell)
 > if the cell is pink, green red or yellow add the cells value to the score 
 > if the cell is blue add twice the value of the cell to the score
 > ***** if the cell is GREEN, then open ALL adjacent cells (that have not
 > been opened already) and treat each of these cells the same way you 
 > treat any cell that gets opened
 > 
 > Output the new board to be sure you opened the correct cells and
 > be sure to report the score of the cell

## Author
Colin McCormaack - cmcco3@ocdsb.ca
