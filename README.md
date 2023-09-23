# SE20UARI139_SchedulingAlgorithms

Q1. Calculating turnaround times: 
FCFS and SJF have the same average waiting time and average turnaround time. These two algorithms perform equally well in terms of these metrics.
PS (Priority Scheduling) has a slightly higher average waiting time and average turnaround time compared to FCFS and SJF. This is because PS may not always prioritize the shortest job or the job with the earliest arrival time.
RR (Round Robin) has the highest average waiting time and average turnaround time among the four algorithms. This is because RR may cause some processes to wait longer due to its fixed time quantum, which doesn't necessarily prioritize short jobs or high-priority jobs.
Conclusion:

In this specific scenario, where the goal is to minimize the average waiting time and average turnaround time, both FCFS and SJF algorithms are equally suitable and perform better than PS and RR.
FCFS and SJF provide the most efficient scheduling in terms of these metrics. 

Q2. Patient data: 
FCFS (First-Come, First-Served):
Efficiency: FCFS is fair in the sense that it follows the order in which patients arrived. However, it may not be the most efficient option, as it doesn't consider the urgency or treatment time of patients. It may result in longer wait times for patients with more critical conditions or longer treatment times.
Fairness: FCFS is fair in the sense that it treats all patients equally based on their arrival times. However, it may not prioritize those who need immediate attention the most.

SJF (Shortest Job First):
Efficiency: SJF is efficient in terms of minimizing wait times because it prioritizes patients with shorter treatment times. This can be advantageous in a busy emergency room to ensure that patients with quick medical needs are seen promptly.
Fairness: SJF may not be the fairest option because it doesn't consider the urgency levels of patients. It could potentially lead to situations where high-urgency cases wait longer if they happen to have longer treatment times.

Priority Scheduling (PS):
Efficiency: PS can be efficient if the priority levels are assigned appropriately, taking into account both urgency and estimated treatment time. It allows for customization based on the hospital's specific priorities.
Fairness: PS can be fair if priorities are assigned in a way that reflects the urgency and medical needs of patients. It provides flexibility to address both urgent cases and those with longer treatment times efficiently.

Round Robin (RR):
Efficiency: RR provides a fair distribution of resources and ensures that all patients get some attention. However, it may not be the most efficient option, especially for critical cases, as it doesn't prioritize based on urgency or treatment time. It can lead to longer wait times for urgent cases.
Fairness: RR is generally fair as it treats all patients equally in terms of time slices. However, it may not be fair in addressing the needs of critically ill patients who may require immediate attention.

In summary:
Efficiency: SJF is the most efficient in terms of minimizing wait times, particularly for patients with shorter treatment times. PS can also be efficient if priorities are assigned appropriately.
Fairness: PS has the potential to be the fairest option as it allows for customization based on the specific priorities of the hospital. FCFS is fair in terms of order of arrival, while RR is fair in distributing resources but may not address urgency effectively.
The choice of the "best" scheduling algorithm depends on the hospital's priorities.
If minimizing wait times and efficiently handling cases with shorter treatment times are top priorities, SJF may be favored.
If fairness in terms of both urgency and estimated treatment time is crucial, PS with carefully assigned priorities could be the best option.
