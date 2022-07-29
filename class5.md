# SMB Port
 
 ## What is an SMB Port?
 
 SMB is a network file sharing protocol that requires an open port on a computer or server to communicate with other systems. 
 SMB ports are generally port numbers 139 and 445. Port 139 is used by SMB dialects that communicate over NetBIOS
 
 ## How Does the SMB Protocol Work?
 
 The SMB protocol creates a connection between the server and the client by sending multiple request-response messages back and forth. Imagine your team is working on a large project that involves a lot of back and forth. You might want to be able to share and edit files that are stored in one place
 SMB was originally designed by Barry Feigenbaum at IBM in 1983 with the aim of turning DOS INT 21h local file access into a networked file system and was originally designed to run on top of NetBIOS over TCP/IP (NBT) using IP port 139 and UDP ports 137 and 138.
 In 1996, Microsoft launched an initiative to rename SMB to Common Internet File System (CIFS) and added more features, including support for symbolic links, hard links, larger file sizes, and an initial attempt to support direct connections over TCP port 445 without requiring NetBIOS as a transport (a largely experimental effort that required further refinement).
 
 ## What are the SMB Protocol Dialects
 
 * SMB 1.0 (1984)
 *  Samba (1992)
 *  CIFS (1996)
 *  NQ (1998)
 * Netsmb (2004)
 *  SMB 2.0 (2006)
 *  Tuxera SMB (2009)
 *  Likewise (2009)
 *  SMB 2.1 (2010)
 *  SMB 3.0 (2012)
 *  MoSMB (2012)
 *  SMB 3.02 (2014)
 *  SMB 3.1.1 (2015)
 *
## Are Open Ports Dangerous?
Open ports become dangerous when legitimate services are exploited through security vulnerabilities or malicious services are introduced to a system via malware or social engineering, cybercriminals can use these services in conjunction with open ports to gain unauthorized access to sensitive data.

## Things I want to know more about
Does SMB require authentication?
