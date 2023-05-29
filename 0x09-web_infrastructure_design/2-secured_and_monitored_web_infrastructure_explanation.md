Description

* For every additional element, why you are adding it:-

. fire wall:- 
is added for security to prevent unauthorized access into or out of a computer network.

. SSL certificate :-
is added for securing data sent between browsers and web servers, datas sent between browsers and web servers is sent 
in plain text—leaving you vulnerable to eavesdropping.

. monitoring clients :- 
is add for to  get deep analytics into how your applications behave, and thus can better serve your customers.
The monitoring clients are for monitoring the servers and the external network. They analyse the performance and operations of the servers,
measure the overall health, and alert the administrators if the servers are not performing as expected. The monitoring tool observes the 
servers and provides key metrics about the servers' operations to the administrators. It automatically tests the accessibility of the s
ervers, measures response time, and alerts for errors such as corrupt/missing files, security vulnerabilities/violations, and many other
issues.

.  Explain what to do if you want to monitor your web server QPS:- 
 There are several tools available to help monitor web server QPS, including open source solutions, commercial products, cloud-based solutions,
 log analysis tools, network monitoring tools and application performance monitoring tools
 
 * issues are with this infrastructure:
 
 . Terminating SSL at the load balancer level means that SSL requests are decrypted at the load balancer and sent unencrypted to the backend via 
 the Droplets’ private IP addresses.
 
 . Having only one MySQL server capable of accepting writes can be an issue because if the master goes down, the application 
  cannot write to the database anymore.
 
 .Having servers with all the same components (database, web server and application server) might be a problem because their consumption will not grow the same way between each of them. 
 For example, you may need to have more database servers than application servers
