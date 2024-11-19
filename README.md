**Explanation to Main.py Code:**

*Read_grid_from_file():*

Reads the file and stores the 3x3 grid as a list of lists (2D array).
Each row in the grid is a list of characters.

*Find_words_in_grid():*

This function searches for words in horizontal, vertical, and diagonal directions.
For horizontal search, it checks each row for the target words.
For vertical search, it checks each column.
For diagonal search, it checks both left-to-right and right-to-left diagonals.
	
*Index Representation:*

For each found word, the code stores the starting and ending positions (row, column indices) of the word in the grid.
The indices are stored as tuples in the dictionary, with the format start: (row, col) and end: (row, col).

*Main Code:*

Reads the 5x5 grid from the file.
Searches for the target words (words_to_find) in the grid.
Prints the found words along with their start and end indices.


*** Before running trhe script ensure poetry is installed

Install Poetry
The link and instructions to install Poetry is below
https://python-poetry.org/docs/#installing-with-the-official-installer

Run the Code
poetry run app
