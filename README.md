# Factory-Simulator
Simulates a factory system that processes nodes that have a number and color each using a queue and three stacks.
The queue holds incoming nodes and the stacks store processed nodes based on their colors
The queue is initialized with 5 random nodes which include random colors, and numbers 
Available colors are Red (r), White (w), Blue (b), and Green (g), and available numbers are 0-9.
The simulation runs for 10 iterations (time steps).R nodes get moved to stack 0, W nodes get moved to stack 1, B nodes get moved to stack 2 and G nodes get moved out of the Queue. At each iteration the current queue state and actions such as moving or discarding queues are displayed and logged.
