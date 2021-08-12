#  Basic Building Blocks

### Internet Protocol
- When the internet was started IP address was assigned for the unique identification of a device.
- The IP v4 was the first type of IP address.
- As IP v4 had limitations of ip's, ipv6 was developed. But IPv6 was not adopted and thus IP v4 is the popular one.
- IANA (Internet Assigned Numbers Authority) is a system that is used to assign IP addresses.

### Classifications of IP

|Class| Address Range|Use|
|-------|------------------|-----|
|Class A|0-127|These are used when we have a big group of hosts |
|Class B|128-191| These are used for medium-size networks.|  
|Class C|192-223|These are used for local area network|

### Port
- It is the entry point to any application.
- We have 65535 ports.
- 0-1023 are the reserved ports used by the system. These can be used only by system administrators.
- 1024 - 49151 are application ports. 3000 - 9999 are the ones used for web applications.
- 49152 - 65535 are the open ports. We should not run the application using this port.  

![ alt text ](images/ip_and_port.jpeg)

### Web Port

- Web ports are the port numbers that are used by HTTP  and HTTPS protocol.
- Port Number 80 is used by HTTP and port number 443 is used by HTTPS.
- These are mainly used by web applications.

### Domain

-  As IP address consists of a series of numbers they are not remembered easily so we cannot search for a site using its IP address.
- To solve this issue **Domain Names** are used.
- The domain names are mapped to an IP address by a system called Domain Name System(DNS).

### Web Servers

- A web server is software or hardware where web applications are hosted.
- It runs only on port 80 or 443.
- Example: Nginx, Apache 2.0

### HTTP  verbs

- The HTTP verbs are as follows:

    - GET: It is used to fetch data
    - POST: It is used to send data to the server.
    - PUT: It is used to send data to the server.
    - DELETE: It is used to delete resources.
    - OPTION: It is used for queries. 

### HTTP Headers

- When a request is sent to or from the server it will have an HTTP header.
- It normally consists information related to the browser i.e which browser is sending a request to the server, etc.
- There are **response** and **request** headers.
- The response header consists the information about the location of the source and the request header consists the information about the request made.

### HTTP Status Codes

- The status codes are used as a response by server to the requests made by clients to the server.

    - 1xx: These are informational.
    - 2xx: All successful requests and responses use this series.
    - 3xx: Anything that requires migration uses this series.
    - 4xx: This are used when there is an error caused by the client.
    - 5xx: This is used when there is an error at the server side.

 ### Software License

 -  We require a software license if we want to work on any software.
 - It provides flexibility and legal protection to the company.
 -  Apache, MIT and BSD are open source and thus provide more flexibility.  They allow us to use the software and modify them and sharing the modified software with the company is not required.
 - While GPL allows us to download the Linux kernel and build an OS using it, but the development must be submitted back to the company.

 - Example: Node.js has MIT license. 

 ###   Databases

 - A database is a form of storage where data is stored in an organized way that makes it easy for accessing, updating and managing.
 - Two types of databases:

    |Relational Database|Non-Relational Database|
    |----|---|
    |Has relations among data| No relation between data that is being used|
    |This consist of tables| As there are no relations among data tables cannot be created|
    |We can perform the join query on tables and data| Join query cannot be|
    |Example: MySQL, Maria DB| Example: MongoDB, Cassandra|

### Cloud Providers

-  It provides a cloud-based platform to host applications.
-  IaaS and PaaS are types of cloud computing services.
- In IaaS we get a server and everything from there will be executed by us and there will be no other support from the company. Example are AWS, Google Cloud, Azure.
- In PaaS, we just have to write the code and commit it and the rest will be executed by the service providers. Examples are Heroku and Netlify.

### Code Repository

- A code repository is very useful when a large number of people are working on the same project.
- It is used for collaboration and software development.
- Github is a proprietary repository and Gitlab and Bitbucket are open source repositories.






