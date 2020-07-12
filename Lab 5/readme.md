# Executive Summary

Explain the goal for this lab: This week is about Flowcharts, Networks, Cybersecurity, and Encription.

## LucidChart

Create a new blank diagram (ignore message boxes to upgrade) and create a flowchart for a computer program that asks for a number and then

* prints "Big" if the number is greater than 10
* prints "Small" if the number is less than 10. 
* Use the following resource (or one of your choice) as a guide: 
https://www.tutorialspoint.com/programming_methodologies/programming_methodologies_flowchart_elements.htm 
* Add a textbox to the chart with your name

Download your chart as a jpg file and name it: DecisionFlowchart and upload the file to your GitHub lab folder

Share your experience using Lucidchart in a paragraph (3-4 lines)

I love flow charts! I have been working with and using flowcharts for a very long time. There are in my current job that show how verious processes work. They are helpful to visualize logic for better understanding. Lucidchart made it simple to create the chart itself, including making it easy to space things evenly. I hade some fun coloring in all the various shapes different colors.

# Networking
## Intro to Networking

## Data Transmission

Match the following words with their definitions 
 
(2) IP Address
* (A) Set of rules to allow devices to communicate Unit of data Unique identifying number 

(1) Packet Packet-Switching 
* (B) Technology that allows packets of data to be routed based on destination address 

(3) DNS Protocol
* (C) Directory of IP address common names. (For example 54.239.26.214 might be the IP address of amazon.com)

## Network Hardware

* Explain the benefit of a switch over a hub.

Switches are intelligent because they are able to learn all the physical addresses of all the devices that are connected to it resulting in computers that receive only the data that is meant for them. Hubs do not filter any of the data and broadcasts it too all connected devides.

* Explain the benefit of a router over hubs and switches.

Hubs and Switches can be used only in LANs whereas routers create networks (WANs) via IP addresses. And not only will routers receive only the data that is intended for them but it bounces all other data along creating a much better security of the data.

## Network Topology

* Explain: Single point of failure and the topologies that experience this issue.

A single point failure is a failure at one point in the network that caudes the whole network go crash because of the topology of that network such as Ring and Bus Networks and Infrastructre Topology.

* Compare the Infrastructure Topology and Wireless Mesh. Which do you think is better and why?

Infrastructre Topology is similar to star topology in that all computers are connected to a central point; so like s Hub and Switch Netorks, when the central point goes down so does the network. In a Wireless Mesh Topology all devices are interconnected to each other. Each wireless access point will talk to other wireless access points creating a seamless internet connection. I would choose WMTs (over Mesh) because are extremely redundant and thus not affected by single point failure. Also, WMTs have no cables or wires making them easire and less expensive to set up.


## Cybersecurity and Encryption

* Imagine you are part of the Amazon.com online chat. Explain how each component of the security triad would impact your job

Confidentility: Amazon must be sure that only those who are authorized to use the online chat are the only ones who have access to it.

Integrity: Information truly repreents its intended meaning and to this end Amazon must provide a network that is immune to power surges and protected from people with malicious intent. For example, there might be a "Malware" integrated into the online chat software.

Availability: Amazon requires their servers to be available 24/7.

* Identify three daily tasks that require authentication. Explain how each one could be converted to multi-factor authentication

Multifactor authenication requires two steps: a thing the user has (an RSD Secure Token) and a thing the user remembers.

Daily Task 1: Using an ATM - The user must have their ATM Card and remember their PIN. 

Daily Task 2: Online Banking - The user must have an ID/password combination and remember the answers to their security questions.

Daily Task 3: Working from home - The user must have VPN for access to The Company plus remeber a password for access into your part of the compnay.

* Explain ACL and RBAC. What are the advantages and disadvantages of each?

ACL: "Access Control list" for each user specific capabilities are assigned.

Advantages: If one is not on the list, they do not even know the resource exists.

Disadvantages: Each resource is managed separately which makes adding or removing a user difficult.

RBAC: An improvement to ACL such that instead of users having specific access rights, roles are developed for the users. 

Advantages: These roles allow administrators to manage the roles and users separately which simplifies administration and improves security. Change aa aspect under the role versus for every individual user. 


* Explain the interaction of ciphertext, a public key and a private key

Ciphertext is a method of encryption that uses a Public Key (anyone can have this to send an encrypted message) and a Private Key (the recipient must have this to decript the message).

* Explain why we need public key cryptography.

This is important so that when poeple send data it is sent with some level of security.

## Cryptography
* Type a message in the "Caesar Cipher Exploration box and turn the wheel to encrypt your message. Then explain the encryption here:

I was able to find a tri-box version online to play with. It did not have a wheel. Box 1 - my message: I do rainbows and smiley faces not not holidays and hearts. Box 2 - Encrypted message: Q lw ziqvjwea ivl auqtmg nikma vwb vwb pwtqliga ivl pmizba. Box 3 - the cypher/shift: This was an 8 letter shift and it looks like gobbltygook.

* Type a message in the "Frequency Fingerprint Exploration" box and a) Explain the result. b) Would it be different for different languages?

(a) I cannot find a version online to play with. (b) It would be differment in different languages because they have different alphabets and their letter frequencies would also be different.

* What is a "Polyalphabetic cipher?" Type a message in the "Polyalphabetic Exploration" box as well as a shift word. Explain the result.

A Polyalphabetic cipher based on substitution using multiple substitution alphabets of whch The Enigma Machine is a more complex version. The message is broken into blocks of equal length, then each position in the box is encrypted using a different simple substitution cipher key. I cannot find a version online to play with.

## Brute Force
* What is Brute-Force and how does it relate to Kerckhoffs's principle?

Kerckhoffs's Principle "states that a cipher should still be secure even if everyone knows how the cipher works and someone else has the ciphertext." If a Brute-Force method can be used to break a cipher then it is not a secure cipher.

# Conclusion
Summarize how this lab was useful to you and what you learnt that really interested you!

Flowcharts are excellent ways of visualizing logic and processes, and there is software theat makes them easy to creat and share. I learned more about how networks can be assembled with various hardware configurations and tolopogy applications. Confidentiality, Integrity, and Availability are the three most importand components of cyber security and how these have been improved to become more dynamic over the decades. Multi-factor authentication is a more secure way to control access to data. I learned about the Caesar and Polyalphabetic ciphers. Frequency Fingerprint analysis and Brute-Force can be used to easily break the Caesar Cipher.
