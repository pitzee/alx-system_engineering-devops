Description

1. What is a server:-
  A server is a computer program or device that provides a service to another computer program and its user, also known as the client. In   a  data center, the physical computer that a server program runs on is also frequently referred to as a server.

2. What is the role of the domain name:-
  Domain Names are used for different purposes, including application-specific naming, addressing, and in various networking contexts to     establish: – Simple identification of hostnames and hosts. Hostnames appear as an element in Uniform Resource Locators (URLs) for           Internet resources, such as web sites.
  
3. What type of DNS record www is in www.foobar.com:-
    www.foobar.com uses an A record. An A record uses a domain name to find the IP address of a computer connected to the internet. The A     in A record stands for Address. Whenever you visit a web site, send an email, connect to Twitter or Facebook, or do almost anything       on     the Internet, the address you enter is a series of words connected with dots.
 4. What is the role of the web server:-
    The primary role of a web server is to store, process, and deliver requested information or webpages to end users. It uses: Physical     Storage: All website data is stored on a physical web server to ensure its safety
    
  5. What is the role of the application server:-
      The function of the application server is to act as host (or container) for the user's business logic while facilitating access to       and performance of the business application.
      
   6. What is the role of the database:-
      The use of a  database is typically involved in efficient data management, a database stores the following: End-user data i.e. raw        ata relevant to the end user. Metadata—the data about data, through which end-user data is integrated and managed.
   
   7.What is the server using to communicate with the computer of the user requesting the website:-
       Web servers and user communicate with web servers using the HyperText Transfer Protocol (HTTP).
  
  what the issues are with this infrastructure:-
  * There are multiple SPOF (Single Point Of Failure) in this infrastructure.For example, if the MySQL database server is down, the           entire site would be down.
  * Downtime when maintenance needed:-
   When we need to run some maintenance checks on any component, they have to be put down or the server has to be turned off. Since          there's only one server, the website would be experiencing a downtime.
   * Cannot scale if there's too much incoming traffic:-
   It would be hard to scale this infrastructure becauses one server contains the required components. The server can quickly                run out of resources or slow down when it starts receiving a lot of requests.

      
