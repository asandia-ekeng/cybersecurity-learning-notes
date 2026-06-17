Cybersecurity Note #12


Ports and Protocols


Introduction

Devices communicate across networks using ports and protocols.

A protocol defines the rules for communication.

A port identifies a specific service running on a device.

Together, ports and protocols allow applications to send and receive data correctly.


What is a Protocol?

A protocol is a set of rules that determines how devices exchange information.

Protocols ensure that devices can understand and communicate with each other.

Examples include:

* HTTP
* HTTPS
* FTP
* SMTP
* SSH

Without protocols, communication between devices would be impossible.


What is a Port?

A port is a logical communication endpoint used by a specific service or application.

Think of an IP address as a building address.

A port is the specific office or room inside the building.

The IP address identifies the device.

The port identifies the service.


Why Ports Matter

Many services can run on a single device.

Ports help direct incoming traffic to the correct application.

For example:

* Web traffic goes to a web service
* Email traffic goes to an email service
* Remote access traffic goes to a remote access service


Common Ports

Port 80

Protocol:

HTTP

Purpose:

Used for standard web traffic.


Port 443

Protocol:

HTTPS

Purpose:

Used for secure web traffic.


Port 21

Protocol:

FTP

Purpose:

File transfer between devices.


Port 22

Protocol:

SSH

Purpose:

Secure remote access to systems.

Widely used by system administrators and DevOps engineers.


Port 25

Protocol:

SMTP

Purpose:

Sending email messages.


Common Networking Protocols

HTTP

Hypertext Transfer Protocol

Used for web communication.

Not encrypted.


HTTPS

Hypertext Transfer Protocol Secure

Encrypted version of HTTP.

Protects sensitive information.


FTP

File Transfer Protocol

Used to transfer files.


SSH

Secure Shell

Provides secure remote access to systems.


SMTP

Simple Mail Transfer Protocol

Used for sending emails.


Ports and Cybersecurity

Ports are important in cybersecurity because attackers often scan systems looking for open ports.

Open ports may reveal:

* Running services
* Potential vulnerabilities
* Misconfigured systems

Security professionals regularly monitor and manage open ports to reduce risk.


Example

When you visit:

https://github.com

Your browser typically connects through:

* Protocol: HTTPS
* Port: 443

The web server listens on that port and responds to your request.


Key Takeaway

Protocols define how devices communicate.

Ports identify which service receives the communication.

Understanding ports and protocols is essential for networking, cybersecurity, cloud computing, and DevOps.


🎯 Reflection

Think about your browser right now.

When you open a secure website, your device is using:

* An IP address
* A protocol
* A port

All of these components work together behind the scenes to deliver the webpage you see.
