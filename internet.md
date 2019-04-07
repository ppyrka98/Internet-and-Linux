# How the Internet Works

#### What is the Internet?
- In basic terms, it is huge system of networks that are interconnected and that follow certain protocols. 


#### How to Read a Web Address
- Example of web address : https://google.com
- Each URL is made up a few 
  components that have a specific meaning to them. the "https://" is the internet protocol for the URL that is required to reach
  the online source. The "google" part of it would be the domain name of the server where the desired information you want is located. 
  The final part of the address ".com" represents the top-level domain, which identifies the website's purpose.
  - For further detail, the "www." would be sub domain, "google" would be the second-level domain, and ".com" the top-level domain.
  
  
#### How does the Internet Work?
- First of all, when you want to travel the internet everyone always starts with opening a client application like 
Chrome or Safari.


- Once it has loaded up, you proceed to type in the URL(Ex:https://www.google.com) for the website you wish to reach. 
This URL sends a request to the DNS(Domain Name Service) server that acts like a phone book, and searches through its system for the IP address(Ex:199.181.33.61)
 that will send you to that page. 

- Now that the IP was found, the browser tries to create a connection to the web server by opening up a socket connection, which is like the web browser checking if the
site is still open, and if it is it connects.

- After being connected to the website, you can now try to request to view a certain part of or information on the website like an article. Before doing this, 
it must check to see TCP/IP and HTTP. These two things will describe how the request you want to make must be formatted when being sent. 
These rules require that the responses and requests made must be cut up into packets of data that know the destination IP address. Once they reach that address they will reassemble
correctly.

- Once the request you sent for has been chopped up, they travel along going through various routers that check and direct the packets to their correct
location. On arrival to the Web Server, the packets reassemble and the server looks for the request you made, chop it into packets again, and send it back.

- After it travels all the way back to your browser, it gets reassembled and translated so that it can be displayed correctly on your screen.

#### SSL secure Website browsing through HTTPS over port 40 vs. HTTP over port 80
- First off, Secure Sockets Layer is the most widely used cryptographic protocol to provide security over internet communications. It offers people a secure channel between two machines 
over the internet
- HTTP is used for unencrypted communication, and means that anyone can intercept the data and be able to read what it says.
- HTTPS is encrypted communication using SSL, and means that the transferred data must be decrypted in our to be read. The only people really able to decrypt and encrypt the data
are the two systems communicating this message.
- The biggest and major difference between these two is that HTTPS is more secure than HTTP because HTTP is subject to having the data being read by someone else who should not be since it is 
transmitted in plain text.
- The port 40 and port 80 that that are referred to here only represent the server port generally used by these two. HTTPS tends to use port 443 and HTTP uses port 80.

#### What is REST and who is Roy Fielding?
- Roy fielding is an American computer scientist and the originator of the Representational State Transfer architectural style
- REST is the the entire Web's architecture. REST is defined through constraints like Statelessness, Cacheability, Resources and representations, Self-descriptive messages, and a bunch of others.

  **What each constraint means**
    - Statelessness means that each request must contain all of the information necessary for the server to understand the request and cannot take advantage of stored context on the server.
    -
-  