# Exact-and-Heuristic-Solution-Approaches-for-Energy-Efficient-Identical-Parallel-Machine-Scheduling

The folder "instances" contains all the data for the 90 instances used in the experimental evaluation.
For each instance <i>i</i> = 1, ... , 90, we encode instance i by means of three different files:
<ul>
  <li>"Data_c<i>i</i>.txt"  :  energy costs of the time slots</li>
  <li>"Data_p<i>i</i>.txt"  :  processing times of the jobs</li>
  <li>"Data_e<i>i</i>.txt"  :  energy consumption rates of the machines</li>
</ul>
The folder "results" contains the results obtained by the solution approaches considered in the paper:
<ul>
  <li><i>Exact algorithm with Formulation 2 (F2)</i>;</li>
  <li><i>Enhanced Heuristic Solver (EHS)</i>;</li>
  <li><i>Exact algorithm with initialization provided by Formulation 2 (F2-init)</i>;</li>
  <li><i>Exact algorithm with Formulation 1 (F1);</i></li>
  <li><i>Split-greedy Scheduler with Exchange Search (SGS-ES).</i></li>.
</ul>
F2-init, EHS, and SGS-ES were run 10 times, due to the presence of at least one stochastic component in the algorithms. For each of such algorithms, the results are organized in 10 different folders within "results/F2-init", "results/EHS", and "results/SGS-ES", respectively. The results obtained with F1 and F2 are contained in "results/F1" and "results/F2".
