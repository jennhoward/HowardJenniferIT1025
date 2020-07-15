# Executive Summary
Include your executive summary here...

This week, it's all about the internet! How it's put together. What was created to make it work seemlessly. How it's secured. How to program for it. 

# Internet Architecture
## Internet Protocol
* What is an IP address and what is the difference between IPv4 and IPv6?

IPv4 is the pool of availalable unallocated addresses for the original Internet Protocol, and the 3.7 billion adresses have been fully allocated to Internet Service Prodivers and users. IPv4 uses four decimal numbers separated by periods for addresses. IPv6 is the next generation of the Internet Protocol which has massively bigger space of 340 undecillion adresses. IPv6 uses hexadecimals separated by colons.

* Find the IP address of your computer by typing ipconfig at the command prompt (refer back to the "Operating Systems" module for details.) Take a screenshot of the command without including the IP address to show your success, name the file ipconfig and upload to the lab folder on GitHub.

There is no command "ipconfig" in the MAC world. I looked up directions on "computer confiruation" and found the directions I screen-shotted with the requested info.

* What is ICANN and how do they contribute to the global Internet?

This entity allocates to the five Regional Internet Registries (RIRs) around the world. The RIRs then allocate smaller IP adress blocks to ISPs and other network operators.

## TCP/IP
### Review the first article and answer these questions:

* What is the responsibility of TCP/IP?

The Transmission cotrolProtocol / Internet Protocol (TCP/IP) is a network protocol that defines the details of how data is sent and received through various communication hardwares. A TCP/IP "port" is like a private 2-way communications line where the port numberis used to identify a unique connection between two devices.

* Explain how the client-server model applies to TCP/IP.

The "client" in the TCP/IP is the device that goes in search of the destination. The "server" is the device that is "on the lookout" for the devices that are seeking that destination. Then the "server" get to decide o allow the "client" in or move it along "it's merry way."

### Review the second article and answer these questions:

Review the section of the article aligning the post office with protocol stacks.

* Why are layers important to changing technology?

Within layered protocol stacks, each stack/layer has a particular task. Each layer communicates only with the level above it and the level below it. The stack is dynamic. Any layer can be moved to another position in the stack without affecting the other layers (whatsoever). A simple change is just that. Before the layers, it was just a single stack, and a small change required re-writing the protocol. 

* What types of applications run on the "application" layer?

The "application" layer runs protocols for SMTP/POP3/IMap4 (email protocols), HTTP (Hypertext Transfer Protocol, the "workhorse" of the web), FTP and SNMP.

## Internet Security
### Watch the video and answer these questions:

* What is HTTP and how does it support the client-server model?

It is the "HyperText Transfer Prococol" and is the most widely used protocol on the internet. The client is the user who types the http of a website to visit. The server is the server that runs the site and lets users in. Unfortunatley when the data is transmitted data, everyone can see it.

* Explain the protocols that secure HTTP uses to protect data.

HTTPS S for secure encrypting the data that is being transferred over the internet by making it impossible to read via encryption algorithms that scramble the data making it impossible to read.

SSL is the "Secure Sockets Layer" Protocol which ensures security on the internet. It uses public key encryption to send a certificate to auhtenticate that trustworthyness of the website.

TLS is the "Transfer Layer Security" that is the successor to SSL, and it uses the latest industry standardized encryption protocol.

### Review the following article: Securing Your Web Browser
* Why should you secure your browser?

Attackers are now exploiting computers via web browsers. Web pages can be disguised to look like a known secure location, like your bank's website, so  when you enter your ID and password, someone else can now access your account. An attacker can exploit a website to install a "trojan" software or spyware both of which will steal your inromation without you even knowing about it.

* Explain one of the risks described in the article.

ActiveX technology allows applications, or parts thereof, to be utilized by a web browser. Unfortunately, this technology has been plagued with vulnerabilties and implementation issues including increasing the "attackability" of a system.When installing Window Applications there's a possibility of downloading another ActiveX into your computer compounding any problems that could occur.

# Internet Programming
* Upload screenshots of your html, css and result

Answer these questions

* Who was Tim Berners-Lee and why did he create the W3C?

He is the inventor of the World Wide Web and wrote the first version of the "HyperText Markup Language" known as HTML. He created W3C to maintain a culture of global particiaption in the developement of the World Wide Web. The organization's work revolves around standardization of Web Technologies which follows processes that premotes the development of high-quality standards via community census.

* Pick a "standard" of your choice and explain why it is important.

"Standard" is a process seeking to maximize consensus to ensure high technology and editorial quality to pormote consistencey among specifications.

* Explain how XML differs from HTML.

XML is a tool used to transport and store data focusing od the data itself. HTML is used to display data focusing on how it looks.

# URLs and File Paths
* Match the following terms / definitions under the heading and explain how they are related by providing an example of all of the pieces of a URL: Terms: scheme, domain, top level domain, default page, parameters, anchor Definitions/examples: .edu, no file path provided, result of search, https, www.amazon.com, specific location on a page.

URL: Uniform Resource Locator

Scheme: This tells the browser what type of address it is so the browser connects to it correctly, like "https" which is a Secure http site.

Domain (Name): This is the most prominent part of a web address, like www.amazon.com.

Top Level Domain: This segment of the address tells you what kind of a site it is, like .edu is for Educational Institutions.

Default Page: This is the entry point of a website which can help you navigate to other pages.

Parameter (String)s: This is a string of characters that beging with a "?" which contains critical information for the server. 

Anchor: This tells the browser to scroll to or load a Specific Location on a Page and begins with a "#".

No Path File Provided: The browser will load a default page if you type in google.com (A Relative Path) versus http://www.google.com (An Absolute Path).

* What is your understanding of difference between Absolute and Relative File Paths. What would you use in your website? Why?

A relative path is one that does not use a full website address; there is no "http//www." at the begining, whereas that absolute path does. See previous question for examples. A relative path link cannot go outside of the current site, so I would use it to go to another place in my current site. An absolute path has all the informatioin necessary to go to any web pahe, thus I would use this to create a link that goes outside of my current site.

* Explain the purpose and use of file compression.

Versus uncompressed files, Compressed files take up less space and can be transferred to other computers more quickly, plus they take less time to upload as well as less time to download.

# Conclusion
Include your conclusion here...
