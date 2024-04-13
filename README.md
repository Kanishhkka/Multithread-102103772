# Multithread-102103772
In this methodology:

1. **Matrix Multiplication Function:** We define `matrix_multiply()` to multiply two matrices using `np.dot()`. The result is stored at a specific index in the result array.

2. **Multithreading Function:** `run_with_threads()` performs matrix multiplication using a specified number of threads. It creates threads for each matrix multiplication operation, starts them, and waits for them to complete. Then, it returns the time taken.

3. **Matrix Definitions:** We generate a constant matrix `A` and a list of 100 random matrices.

4. **Execution:** We call `run_with_threads()` for each number of threads from 1 to 10, recording the time taken for each operation in `results_table`.

5. **Results:** The results are displayed in a table format using `tabulate()`.

6. **Plotting:** We plot the number of threads against the corresponding time taken using `matplotlib.pyplot.plot()` and display the plot.

**Observation:** The time taken is minimum when the number of threads is 8, which is expected since there are 8 cores on my laptop.
<img src="![Result](https://github.com/Kanishhkka/Multithread-102103772/assets/107942421/9c2c8618-08bc-4d5d-952f-055171a1a390)
">
