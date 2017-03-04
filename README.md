# ros-turtlesim-
The whole turtle sim arena is to be mapped into a 10x10 grid.
There are numbers 1-10 positioned at random squares in the arena. They won’t be known unless a turtle reaches that square in the grid and sends a call to the “Check Function” 
The function will return one of the following integers as a reply:    
0 – if the square does not contain any number and is not an obstacle    
1 – if the square contains a number but it is not the one that is being searched for. This square is an obstacle and cannot be traversed.
2 – if the square contains the number that is being searched for. This square too is an obstacle and cannot be traversed.
