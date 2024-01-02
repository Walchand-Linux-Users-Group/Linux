# top
top – to show the Linux processes
## Description 
It provides a dynamic real-time view of the running system also, It displays a continuously 
updated list of processes along with information on CPU utilization, memory usage, and 
other key statistics. 
## Syntax 
top 
## Options/Flags 
   ### • Specifies the delay between updates. 
     $ top -d <delay> 
   ### • Limits the number of iterations or updates before exiting. 
     $ top -n <iterations> 
   ### • capture output for scripts or further processing 
     $ top -b 
   ### • Shows the full command path for processes. 
     $ top -c 
   ### •  Ignores case when sorting by command name 
     $ top -i 
   ### • Limits display to processes owned by a specific user. 
     $ top -u <username> 
   ### • Displays information only for the specified process ID. 
     $ top -p <process_id> 
   ### • skipping summary information at the top of the display. 
     $ top -q 
   ### • Displays a help message with information about available options. 
     $ top -h
## Author
    • Roger Binns.