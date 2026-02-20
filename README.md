Process-Scheduler : This project demonstrates how multiple system tasks can be orchestrated through a single program. The application integrates scheduling algorithms, performance analysis, and graph visualization into one workflow. The goal of the project is to provide a practical demonstration of Operating System scheduling concepts along with automated performance analysis.


FEATURES -   
          * The simulator implements various CPU scheduling algorithms like  FCFS, SJF(non-preemptive),SRTF & Round Robin algorithm.
					*Each algorithm runs on the same set of processes for accurate comparisons. 
					The program calculates waiting time,turnaround time and completion time. Using these metrics, it automatically recomends the best scheduling algorithm based on the lowest average waiting time.
					*GANTT CHART visualization-For every scheduling algortihm, the program prints a gantt chart in the console showing execution order of processes, cpu idle times and tinme inmtervals of each process.
					*Performance Graphs using GNUPLOT: The simulator generates data files and plot graphs such as:  1.Waiting time comparisons between algorithms. 2. Scalability (number of processes vsn average waiting time) 3.Average turn around time trends.


TECHNOLOGIES USED: * C++ for integrated execution of distinct tasks in single code.
							     * GNUPLOT for data visualization.
									 *File handling for generating plot data.
