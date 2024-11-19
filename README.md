Explanation to Main.py Code:
1.	Read_grid_from_file():
2.	Reads the file and stores the 3x3 grid as a list of lists (2D array).
3.	Each row in the grid is a list of characters.
4.	
5.	Find_words_in_grid():
6.	This function searches for words in horizontal, vertical, and diagonal directions.
7.	For horizontal search, it checks each row for the target words.
8.	For vertical search, it checks each column.
9.	For diagonal search, it checks both left-to-right and right-to-left diagonals.
10.	
11.	Index Representation:
12.	For each found word, the code stores the starting and ending positions (row, column indices) of the word in the grid.
13.	The indices are stored as tuples in the dictionary, with the format start: (row, col) and end: (row, col).
14.
15.	Main Code:
16.	Reads the 5x5 grid from the file.
17.	Searches for the target words (words_to_find) in the grid.
18.	Prints the found words along with their start and end indices.


*** Before running trhe script ensure poetry is installed

Install Poetry
The link and instructions to install Poetry is below
https://python-poetry.org/docs/#installing-with-the-official-installer

Run the Code
poetry run app
