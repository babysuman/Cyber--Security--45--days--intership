# \# Ports \& Services in networking:



1. ### Port:

###### &#x20;          > A port is a logical identifier used to distinguish different applications or services 

###### &#x20;             on a device, allowing network traffic to reach the correct program.

###### &#x20;          > Ports work at the Transport layer, using TCP and UDP to send and receive data between devices.

###### &#x20;          > They enable multiple applications to use the network simultaneously without interference.

###### &#x20;          > Ports help the operating system route incoming data to the appropriate application.



* #### How Ports Work:

###### &#x20;                   > When a device communicates over a network, data packets are sent to its IP address. Each packet also includes a port    

###### &#x20;                     number, which tells the operating system which application or service should receive that data.



##### &#x20; a) Port numbers identify services:

###### &#x20;                                      > Each application listens on a specific port, so incoming data reaches the correct program.

##### &#x20; 

##### &#x20; b) IP + Port + Protocol = Socket:

###### &#x20;                                     > This combination ensures that network traffic is delivered precisely to the right process on the right 

###### &#x20;                                       device.



##### &#x20; c) TCP and UDP protocols use ports differently: 

###### &#x20;                                      > TCP ensures reliable delivery, while UDP is faster but without guaranteed delivery.



* #### Types of ports:

###### &#x20;                    > Ports are mainly classified into the following types:

###### 

##### &#x20; 1. Physical Ports:

###### &#x20;                     > These are actual hardware connectors on devices.

###### &#x20;                       Examples include USB for keyboards and storage devices, Ethernet (RJ-45) for network connections, HDMI for video, and     

###### &#x20;                       audio ports for sound.

###### &#x20;                     > These are any connector you can plug a device into.



##### &#x20; 2. Logical/Network Ports:

###### &#x20;                        > These are software-based endpoints that let programs communicate over a network.

###### &#x20;                        > Each port is numbered from 0 to 65535 and is divided into different groups.

###### 

###### &#x20;                        a) Well-known Ports (0–1023): Reserved for standard services like HTTP (80), HTTPS (443), FTP (21), SSH (22).

###### &#x20;                        b) Registered Ports (1024–49151): Used by specific applications like databases (MySQL 3306, SQL Server 1433).

###### &#x20;                        c) Dynamic/Private Ports (49152–65535): Temporarily assigned for client connections, like when your browser opens a port to connect to a website.

###### &#x20;                                                                Internal Ports only used inside your private network (LAN) for local communication between devices.

###### &#x20;                                                                External Ports are open to the internet, routers map them to internal ports so external users can access  

###### &#x20;                                                                services safely.



##### &#x20; 3. Serial and Parallel Ports:

###### &#x20;                                    > Older hardware ports mostly used before USB became standard.

###### &#x20;                                    > Serial Ports (COM) transmits data one bit at a time, often used in industrial equipment.

###### &#x20;                                    > Parallel Ports (LPT) send multiple bits at once, historically used for printers.

##### &#x20; 

##### &#x20; 4. Virtual Ports:

###### &#x20;                      > Software-defined ports used in virtual machines, containers, or applications to communicate internally without physical hardware.

###### &#x20;                      > Useful for running multiple services on one device or isolating network traffic.



* #### Common port :

###### &#x20; There are  65,535 no of ports and port no. range from 0-65535. 

|**PORT NO.**|**Description**|
|-|-|
|7|Echo service|
|20-21|FTP-data and FTP(file transfer protocol)|
|22|SSH(secure shell)|
|23|Telnet(telnet protocol - unencrypted text communication.)|
|25|SMTP(simple mail transfer protocol)|
|53|DNS(domain name system).|
|67/68|DHCP(dynamic host configuration)|
|80|HTTP(hyper text transfer protocol)|
|110|POP3(post Office protocol version)|
|443|HTTPS(hypertext transfer protocol secure)|
|3306|MySQL(my structured query language)|
|3389|RDP(remote desktop protocol)|



### 

### 2\. Services:

###### &#x20;                  > Network services refer to the applications or services that are hosted on a network to provide functionality for users or other applications. 

###### &#x20;                  > Examples of network services include:

###### 

###### &#x20;                  > File Service: Enables files to be shared and stored on a central server.

###### &#x20;                  > Print Service: Manages print jobs over a network.

###### &#x20;                  > Messaging (Email) Service: Enable sending, receiving, and storage of emails.

###### &#x20;                  > Database Service: Provides centralized access to databases.

###### &#x20;                  > Web Service: Hosts and delivers web pages to users.

###### &#x20;                  > DNS Service: Translates domain names into IP addresses.

###### &#x20;                  > DHCP Service: Dynamically allocates IP addresses to devices on a network.



* #### Types of services:

###### &#x20;  There are mainly 6 type of services.

##### &#x20; 1. Naming \& Configuration Services:

###### &#x20;              > These services automate network communication so devices can easily find and talk to each other without manual setup.

##### &#x20; 

##### &#x20; 2. File, Print \& Resource Sharing:

###### &#x20;              > These services allow centralized management and access to physical hardware and digital files across the network.

##### 

##### &#x20; 3. Communication \& Application Services:

###### &#x20;              > These services enable human interaction and data exchange across an interconnected network environment.



##### &#x20; 4. Security \& Access Services:

###### &#x20;              > These services protect the network from unauthorized access, cyber threats, and secure traffic passing across public networks.



##### &#x20; 5. Network Management \& Optimization:

###### &#x20;              > These services help administrators monitor network health, manage devices, and prioritize performance.



##### &#x20; 6. Cloud \& Virtualization Services:

###### &#x20;              > Modern networks often rely on off-premises, cloud-hosted resources to scale operation.

###### 













