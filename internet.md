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