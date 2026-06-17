Cybersecurity Note #11

HTTP vs HTTPS

Introduction

Whenever you visit a website, your browser communicates with a web server.

This communication usually happens through HTTP or HTTPS.

These protocols define how information is exchanged between your device and a website.

Understanding the difference between HTTP and HTTPS is important in cybersecurity because it directly affects the security of data transmitted online.


What is HTTP?

HTTP stands for:

Hypertext Transfer Protocol

It is the standard protocol used for communication between web browsers and web servers.

HTTP allows users to:

* Visit websites
* Load web pages
* Send requests
* Receive information

However, HTTP does not encrypt data.


How HTTP Works

When you enter a website address:

1. Your browser sends a request
2. The web server receives the request
3. The server sends back the webpage

The communication happens openly across the network.

Anyone intercepting the traffic may be able to view the transmitted information.


Risks of HTTP

Because HTTP does not encrypt data, attackers may be able to:

* Read sensitive information
* Intercept login credentials
* Monitor network traffic
* Steal transmitted data

This makes HTTP unsuitable for websites handling sensitive information.


What is HTTPS?

HTTPS stands for:

Hypertext Transfer Protocol Secure

HTTPS is the secure version of HTTP.

It protects information by encrypting data before transmission.


How HTTPS Works

HTTPS uses:

SSL/TLS Encryption

This encryption ensures that:

* Data remains private
* Information cannot easily be read by attackers
* Communication is protected during transmission

When you visit an HTTPS website, data is encrypted before leaving your device.


Identifying HTTPS Websites

Most browsers display:

🔒 A padlock icon

in the address bar.

Example:

https://github.com

The “S” in HTTPS stands for Secure.

HTTP vs HTTPS Comparison

HTTP

* Full Meaning: Hypertext Transfer Protocol
* Encryption: No
* Data Protection: Low
* Security: Vulnerable
* Default Port: 80

HTTPS

* Full Meaning: Hypertext Transfer Protocol Secure
* Encryption: Yes
* Data Protection: High
* Security: More Secure
* Default Port: 443

  Why HTTPS Matters

HTTPS helps protect:

* Passwords
* Personal information
* Banking details
* Payment information
* Login credentials

Most modern websites use HTTPS because security is essential for online communication.


HTTPS and Cybersecurity

Cybersecurity professionals encourage organizations to:

* Use HTTPS
* Maintain valid SSL/TLS certificates
* Encrypt sensitive communications

HTTPS helps reduce the risk of:

* Data theft
* Eavesdropping
* Man-in-the-middle attacks


Example

Imagine logging into a website.

Using HTTP:

* Username and password may travel unencrypted.

Using HTTPS:

* Credentials are encrypted before transmission.

This significantly improves security.


Key Takeaway

HTTP is used for web communication but does not encrypt data.

HTTPS adds encryption and protects information during transmission.

For secure online communication, HTTPS should always be preferred over HTTP.


🎯 Reflection

The next time you visit a website, look at the address bar.

Do you see:

🔒 HTTPS

or

⚠️ HTTP

That small difference plays a major role in protecting your information online.
