# PythonTraining
This repository contains Jupyter notebooks with comment lines, comment cells and outputs that explain the functionality of different libraries in Python. These guidelines include basic Python programming, Numpy, Pandas, Matplotlib, Seaborn and more. I hope it guides you to start your programming experience! Below you have more details of the content.



# 1. Data types and loops
Content:
- Arithmetic
    - Math library
    - Formatting
- Lists
    - Mutability
    - Slice notation
    - append a value
    - insert a value (needs an index)
    - extend (merges one list)
    - pop (remove value from list)
    - len
    - range
    - sort
    - reverse
- Strings
    - Docstrings
    - Escape Sequences
    - String Concatenation
    - Character Sets (ASCII)
    - Print datetime using f-string format
- Dictionaries
    - General operations
    - Get a dictionary of unique values from a text (create a SET object)
    - use dictionary to count repeated elements with SET and without SET
- Loops
    - Augmented Assignment
    - Calculator: Convert numbers from binary, octal or any other system to decimal
- Text Files
- os library
    - Create Folder
    - Rename Folder
    - Search folders
    - Remove Folders


# 2. Functions and classes
- Functions
    - Abstraction Mechanisms
        - Eliminating Redundancy
        - Systematic variations
    - main function
- Classes
    - help
    - __init__ method
    - Objects
    - Instance variable
    - Atttributes
    - Methods
    - __dict__ method
    - __str__ method
    - Types of Methods
    - Inheritance


# 3. NUMPY Fundamentals
- Create Arrays and Grids
    - One dimension array
    - Two dimension array
    - Zeros array
    - Ones array
    - X value array
    - Eye Matrix (identity matrix)
    - Create arrays using a range
    - Create array with linear interpolation
    - Create array with random numbers
- Get Attributes
    - Dimension of array
    - shape of array
    - Data type inside array
    - Size of the array
- shape manipulation
    -Re-shape
- Operations with Numpy
    - Sum, substract, divide, multiply
    - Sort
    - Concatenate
    - Sum, mean, min and max functions
    - Indexing and slicing
    - Copy
    - Save
    - Save as txt or csv
    - Load
    - Conditionals
    - Unique function
- Broadcasting

# 4. PANDAS Fundamentals
- Create DF
    - Create Dummy DF
    - Copy DF to another variable
    - add / drop columns
    - Re-order / Re-name columns
    - add / drop rows
    - delete df
- Visualize df
    - Header and Tail
    - Columns
    - info
    - describe
    - Correlation
    - unique values
    - Sort data / Specific order of elements in columns
    - Slice Columns
    - Show data based on conditions
    - Group By
- Modify Data
    - Replace
    - Map
    - get dummies
    - Missing Data
    - astype
    - interpolate
    - lambda expression with datetime
- Plotting with Pandas

# 5. MATPLOTLIB Fundamentals
Coming soon!

# 6. SEABORN Fundamentals
- Create Dummy DF
- Pairplot
- barplot
- heatmap
- heatmap - quick way to plot missing data in dataframe
- More coming soon

# 7. Time Series data with PANDAS
- DateTime Index Basics
- Time Resampling
- Time Shifting
- Rolling and Expanding
- Time Series Visualization

# 8. STATSMODEL Fundamentals
- DateTime Index Basics
- Time Resampling
- Time Shifting
- Rolling and Expanding
- Time Series Visualization

# 9. PYTORCH Fundamentals
- **Reference information**
- **Create Tensors**
    - torch.randint
    - torch.arange
    - torch.arange with trick to make them float
    - torch rand (return scalars between 0 and 1)
    - torch.randn (return scalars from the standard normal dist)
    - torch.linspace
    - torch.empty
    - torch.zeros
    - torch.zeros_like (Returns tensor filled with 0s with the same size as input.
    - torch.ones
    - torch.ones_like
    - torch.full
- **Convert to Tensors**
    - from_numpy
    - as_tensor
    - tensor and Tensor (One converts to int and the other float)
    - FloatTensor
- **Handle Tensor Dimensions**
    - reshape (this function will copy the underlying data)
    - view   (this function will not copy the underlying data)
    - view_as
    - unsqueeze
    - Use of None expression
    - Slice Notation for Even Numbers
    - Slice Notation for Odd Numbers
    - Handle Tensor Ops based on dimensions
- **Tensor Operations**
    - Change Tensor type
    - torch.cat
    - torch.stack
    - Matrix Transpose
    - Permute
    - torch.where
    - Slice Notation
    - Math Ops
- **Tensor Attributes**
    - Shape or Size (same thing)
    - Device (CPU or GPU)
    - Layout
    - Mean
    - Max
    - argmin, argmax
    - sum
    - unique
- **Probability Dist Functions**
