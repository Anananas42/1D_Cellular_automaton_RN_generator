# 1D_Cellular_automaton_RN_generator (2019)
My first somewhat interesting programming project with very inefficient, but beautiful visualization of 1D CA with configurable settings and basic statistics to measure randomness.

## How to use
Run the Cellular Automata.exe to start the Unity application.

- Left column indicates how many times each number has been generated by converting states of 4 pixels in the last row of the generated cells.
- Green square can be used to stop/start generation.
- 'T' shapes can be used to specify current rules by clicking on the bottom cube. It indicates what the state of a following cube will be based on its 3 upper neighbours.
- '%' button changes absolute amount of generated numbers to percentages of each number being generated compared to the total amount of generated numbers. (Basic condition for a good pseudorandom number generator is having a uniform distribution)
- 'Reset Sums' Resets counters for all numbers
- 'Randomize' Chooses a random initial state
- 'Reset' Resets the whole grid
- '+1' Advances by 1 iteration
- '+10' Advances by 10 iterations
- 'infinity' Enables to run continuously using the green square

![image](https://user-images.githubusercontent.com/43809508/139271880-a2fc2ffd-f8d4-41ff-b23a-4904642025cb.png)
