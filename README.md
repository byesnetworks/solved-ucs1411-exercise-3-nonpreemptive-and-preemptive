Download Link: https://assignmentchef.com/product/solved-ucs1411-exercise-3-nonpreemptive-and-preemptive
<br>
3  Implementation of CPU Scheduling Policies: FCFS and SJF (Nonpreemptive and Preemptive)

Develop a menu driven C program to implement the CPU Scheduling Algorithms

FCFS and SJF (Non-Preemptive and Preemptive)

<u>Sample Learning Outcome:</u>

<ol>

 <li>Learn about the CPU Scheduling algorithms – FCFS and SJF.</li>

 <li>Implement the sorting algorithms necessary for scheduling and analyzing the performance using waiting time, turn around time and response time.</li>

 <li>Learn to draw the Gantt Chart <u>Best Practices:</u></li>

 <li>Algorithm design</li>

 <li>Naming convention – for file names, variables</li>

 <li>Comment usage at proper places</li>

 <li>Prompt messages during reading input and displaying output</li>

 <li>Error handling mechanisms for failures in system calls</li>

 <li>Incremental program development</li>

 <li>Modularity</li>

 <li>All possible test cases in output</li>

</ol>

<u>Algorithm:</u>

<ol>

 <li>Read the following

  <ol>

   <li>Number of processes</li>

   <li>Process IDs</li>

   <li>Arrival time for each process</li>

   <li>Burst Time for each process</li>

  </ol></li>

 <li>Design a menu with FCFS and SJF options</li>

 <li>Upon selection of menu option apply the corresponding algorithm.</li>

 <li>Compute the average turnaround time, average waiting time and average response time for each of the algorithm.</li>

 <li>Tabularize the results.</li>

 <li>Display the Gantt Chart.</li>

</ol>

<u>Sample Input &amp; Output:</u>

CPU SCHEDULING ALGORITHMS

<ol>

 <li>FCFS</li>

 <li>SJF</li>

 <li>EXIT</li>

</ol>

Enter your option: 1

FCFS CPU SCHEDULER

Number of Processes: 5

Process ID:  P1

Arrival Time: 0

Burst Time:  4

–

–

–

Process ID:  P5

Arrival Time: 6

Burst Time:  3

<u>Output:</u>

<table width="0">

 <tbody>

  <tr>

   <td width="122">              P1</td>

   <td width="122"> </td>

   <td width="122"> </td>

   <td width="122"> </td>

   <td width="122"> </td>

  </tr>

 </tbody>

</table>

0                          4




<table width="0">

 <tbody>

  <tr>

   <td width="144">              P1</td>

   <td width="48">   0</td>

   <td width="344">       4                ***                   ***                    ***</td>

  </tr>

  <tr>

   <td width="144">                ***</td>

   <td width="48">  ***</td>

   <td width="344">      ***              ***                  ***                        ***</td>

  </tr>

  <tr>

   <td width="144">            ******</td>

   <td width="48"> </td>

   <td width="344"> </td>

  </tr>

  <tr>

   <td width="144"> </td>

   <td width="48"> </td>

   <td width="344">                         Average          ***                          ***</td>

  </tr>

 </tbody>

</table>

Process ID            Arrival Time   Burst Time Turnaround Time Waiting Time    Response Time




Want to Continue ( Y/N): Y

CPU SCHEDULING ALGORITHMS

<ol>

 <li>FCFS</li>

 <li>SJF</li>

 <li>EXIT</li>

</ol>

Enter your option: 2

SJF CPU SCHEDULER

<ol>

 <li>Non preemptive SJF</li>

 <li>Pre emptive SJF</li>

</ol>

Enter your option: a

Number of Processes: 5

Process ID:  P1

Arrival Time: 0

Burst Time:  4

–

–

–

Process ID:  P5

Arrival Time: 6

Burst Time:  3

<u>Output:</u>

<table width="0">

 <tbody>

  <tr>

   <td width="122">              P1</td>

   <td width="122"> </td>

   <td width="122"> </td>

   <td width="122"> </td>

   <td width="122"> </td>

  </tr>

 </tbody>

</table>

0                          4




<table width="0">

 <tbody>

  <tr>

   <td width="192">***</td>

   <td width="48">***</td>

   <td width="144">   ***</td>

   <td width="96">***</td>

   <td width="48"> </td>

   <td width="44">***</td>

  </tr>

  <tr>

   <td width="192">                                *********</td>

   <td width="48"> ***</td>

   <td width="144">    ***</td>

   <td width="96"> ***</td>

   <td width="48"> </td>

   <td width="44">  ***</td>

  </tr>

  <tr>

   <td width="192"> </td>

   <td width="48"> </td>

   <td width="144">            Average</td>

   <td width="96">   ***</td>

   <td width="48"> </td>

   <td width="44">   ***</td>

  </tr>

 </tbody>

</table>

Process ID             Arrival Time   Burst Time  Turnaround Time Waiting Time  Response Time