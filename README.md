# Multithread-102103772
**Google Colab:**
<a href="https://colab.research.google.com/drive/1bnK8x4ZfO82qIXPiYSCCyvNtCltjdvJQ?usp=sharing">Click Here</a><br>
In this methodology:

1. **Matrix Multiplication Function:** We define `matrix_multiply()` to multiply two matrices using `np.dot()`. The result is stored at a specific index in the result array.

2. **Multithreading Function:** `run_with_threads()` performs matrix multiplication using a specified number of threads. It creates threads for each matrix multiplication operation, starts them, and waits for them to complete. Then, it returns the time taken.

3. **Matrix Definitions:** We generate a constant matrix `A` and a list of 100 random matrices.

4. **Execution:** We call `run_with_threads()` for each number of threads from 1 to 10, recording the time taken for each operation in `results_table`.

5. **Results:** The results are displayed in a table format using `tabulate()`.

6. **Plotting:** We plot the number of threads against the corresponding time taken using `matplotlib.pyplot.plot()` and display the plot.

**Observation:** The time taken is minimum when the number of threads is 8, which is expected since there are 8 cores on my laptop.
A dashboard is created using **ipywidgets** with various refresh rates generating random matrices.
<img src="https://github.com/Kanishhkka/Multithread-102103772/blob/main/Result.png">
