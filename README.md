Question 1 : Print the numbers from 1 to 10 in random order to the terminal 

Kindly run the file using this command in macos and linux :  python <filename>

I have used the random module here to print random numbers from 1 to 10.


Question 2 : Imagine a server with the following specs:
- 4 times Intel(R) Xeon(R) CPU E7-4830 v4 @ 2.00GHz
- 64GB of ram
- 2 tb HDD disk space
- 2 x 10Gbit/s nics
The server is used for SSL offloading and proxies around 25000 requests per second

Answer : The basic metrics that will be monitored are 
 a) 5xx error code 
 b) 4xx error code & 3xx error code
 c) Active Sessions
 d) Target TLS negotiation error & Client TLS negotiation error
 e) Average response time 
 f) Denied Sessions
 g) Queue Time
 h) Data (Amount of data sent between proxy server and client) 
 i) Warnings (no of retries and redispatches)
 l) Server status (health of server)
 j) CPU utilisation of instance
 k) Memory utilisation of instance
 
 These will be my basic metrics for monitoring the instance.
 
 In order to configure these metrics and alerts i would use tools like Nagios or Grafana and i would setup and alert so that when ever the valuen goers above the given threshold it would trigger an email to the devops team.
 
 The main challenge of setting up these alerts would be configuring the proper threshold value and keeping a close watch on all the graphs all the time.
