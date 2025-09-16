# Experiment-3

# Problem 1

The program to Problem 1 begins by importing Pandas and loading the dataset cars.csv into a DataFrame named cars. This step is essential, as it converts the external CSV file into a structured format that can be easily manipulated and analyzed. By displaying the DataFrame immediately after loading, the code allows verification that the dataset has been successfully imported and is ready for use.

The program then used the head() function, which shows the first five rows of the DataFrame. This preview helps confirm the structure of the data and reveals the initial entries of the table. Following this, the tail() function was used to display the last five rows, which provides insight into the ending portion of the given dataset. Together, these two functions give a quick overview of the dataset from both ends and ensure its completeness.

The last line of the program converts the program into a Python script or .py file by using the to_csv() function. 


# Problem 2

The program to Problem 2 begins by importing Pandas and loading the cars.csv file into a DataFrame called cars. With the dataset prepared, the code then demonstrates different ways to access subsets of the data using indexing and selection functions.

The first operation uses the iloc[] to extract the first five rows of only the odd-numbered columns. The function cars.iloc[0:5, [1,3,5,7,9,11]] specifies the range of rows and the particular column positions, effectively narrowing the dataset to a smaller, more targeted table. A print() statement is included to label the output, making it clear what is being displayed.

Next, the program isolates a single row of data by applying slicing notation with cars[0:1]. This retrieves the first row of the DataFrame while still keeping it in tabular form. Following this, the loc[] function is used to select rows and columns based on their labels. For example, cars.loc[[23], ['Model', 'cyl']] retrieves the 23rd row while focusing only on the columns “Model” and “cyl.” Similarly, cars.loc[[1,28,18], ['Model', 'cyl', 'gear']] selects three specific rows and limits the output to three chosen columns. 

The same with Problem 1, the last line of the program converts the program into a Python script or .py file by using the to_csv() function. 
