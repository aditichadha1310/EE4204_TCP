[Jumping Window Protocol]: Develop a TCP-based client-server socket program 
for transferring a large message using a hypothetical jumping window protocol. Here, 
the message transmitted from the client to server is read from a large file. The 
message is split into short data-units (DUs) which are sent and acknowledged in 
batches of size n. The sender sends n DUs and then waits for an ACK before sending 
the next batch of n DUs. It repeats the above procedure until the entire file is sent and 
the acknowledgement for the last batch is received. The receiver sends an ACK after 
receiving n DUs. It repeats the above procedure, until the acknowledgement for the 
last batch is sent. Note that the last batch may have less than n DUs.
Verify if the file has been sent completely and correctly by comparing the received 
file with the original file. Measure the message transfer time and throughput for 
various sizes of data-units. Choose appropriate values for “data unit size” and 
measure the performance. Repeat the experiment several times and plot the average 
values in a report with a brief description of results, assumptions made, etc.
Carry out the above experiments for three different batch size values: n=1, n=2, and 
n=4. Note that when n=1, this jumping window protocol becomes similar to the stopand-wait protocol. Include the following two performance figures in your report: 
a. Transfer time vs data unit size ( with three curves one each for n=1, n=2, and 
n=4) 
b. Throughput vs data unit size ( with three curves one each for n=1, n=2, and 
n=4 )