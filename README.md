# CPU Scheduling with OS
Operating System with C Language

**<h2>Page Replacement Algorithm</h2>**
<h3>Goal</h3>
We make CPU simulators using C language<br>

<h3>Description</h3>
Simulates CPU scheduling algorithms (FCFS, SJF, SRTF, Priority, and Round Robin), calculate waiting time, average turnaround time.<br>

<h3>Input</h3>
Input is in a proc.txt file in the form:<br>

|Process#|CPU_time|Arrival_time|Priority|
|---| ---|---| ---|
|entry|entry|entry|entry|
|entry|entry|entry|entry|
|.|.|.|.|
|.|.|.|.|
|.|.|.|.|

<br>
Notes:

1. You have to enter JUST the entries (anything under "-------").
2. Number of spaces between each entry does NOT matter.
3. All the entries MUST BE integers.
4. Don’t leave any spaces or enters after last of input
5. Don’t give zero for a process CPU time
6. No processes come in the same time
<br>

<h3>Running Example</h3>

$> cpu_scheduling <enter><br>
 Main Menu<br>
—————
* Read processes from proc.txt<br>
 Generate random processes<br>
 First come first Serve (FCFS)<br>
 Shortest Job First (SJF)<br>
 Shortest Remaining time First (SRTF)<br>
 Priority<br>
 Round Robin (RR)<br>
 Exit<br>
 *** Note: User the arrow keys to choose from the menu<br><br> 
 
 
<h4>CPU scheduling explain: https://kim-hoya.tistory.com/11</h4>
<h4>My code explain: https://kim-hoya.tistory.com/22</h4>
