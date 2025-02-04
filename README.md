# ZeroDivisionError in average calculation function
This repository demonstrates a common error in Python: the ZeroDivisionError that can occur when calculating the average of a list of numbers.
The function `calculate_average` raises this error if it is given an empty list. This is because it attempts to divide by the length of the list, which is 0 in the case of an empty list.
The solution involves adding an error handling mechanism (try-except block) or a check to make sure the list is not empty before performing division.