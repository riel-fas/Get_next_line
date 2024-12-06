# GET_NEXT_LINE
Get_next_line

Key Features:
Handles multiple file descriptors simultaneously.
Custom buffer size to optimize performance for different use cases.
Efficient memory management for handling large or unpredictable inputs.
Function Prototype


Parameters:

>fd — The file descriptor to read from.

Return Value:

>A pointer to the next line read from the file descriptor.

>NULL if an error occurs or the end of the file is reached.


Mandatory Requirements

>The function reads one line at a time, delimited by \n.

>It works with any valid file descriptor (standard input, files, etc.).

>Successive calls to get_next_line continue reading where the previous call left off.

>The function should handle multiple file descriptors without interference.

>The function must be leak-free and manage memory effectively.

Bonus Features

>Support for multiple file descriptors simultaneously.

>Optimized to handle extremely large files or very small buffer sizes.

