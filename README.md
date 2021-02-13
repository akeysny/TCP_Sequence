# TCP_Sequence

- [x] We are going to be reviewing Session Hijacking.

- [x] When we are talking Session Hijacking we are talking an ability of a tester or an attacker to take control of a communication between the user and the host service during their session.

- [x] Attacker is gaining access without authenticating because the user already is.

- [x] Communicating across the Internet requires the user to use the protocol, one of which we are going to review and known as Transmission Control Protocol or TCP.

- [x] IP address carries the packet and TCP provides the control for enabling the session to be created.

- [x] We are going to be using Wireshark to disect the communication packets.

- [x] When we first click on our web server, the first thing that happens is an establishment of a TCP connection.

- [x] We are going to set Wireshark to capture packets while starting our Web Browser session.

App Walkthrough GIF

<img src="http://g.recordit.co/thzeuM61AX.gif" width=250><br>

- [x] We will notice a number of DNS packets to start with, we will be looking specifically at TCP oackets here

App Walkthrough GIF

<img src="http://g.recordit.co/M1GrNdsvtX.gif" width=250><br>
