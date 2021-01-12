# Port-Scanner
In the given program, we need to import the stringing module, which is inbuilt in the Python bundle. We are utilizing the string locking idea, thread_lock = threading.Lock() to maintain a strategic distance from different change at a time. Fundamentally, threading.Lock() will permit single string to get to the variable at a time. Thus, no twofold adjustment happens. 

Afterward, we characterize one threader() work that will bring the work (port) from the laborer for circle. At that point the portscan() technique is called to associate with the port and print the outcome. The port number is passed as boundary. When the assignment is finished the q.task_done() strategy is called. 

Presently subsequent to running the above content, we can see the distinction in speed for checking 50 to 500 ports. It just required 1.3589999675750732 seconds, which is under 452.3990001678467, time taken by attachment port scanner for filtering similar number of ports of localhost.
