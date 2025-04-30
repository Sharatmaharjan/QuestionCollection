## 5 Marks Questions

### **1. Introduction**  
1. Explain the client-server model with a diagram. How does it differ from peer-to-peer architecture?  
2. Compare and contrast different network programming languages, tools, and platforms.  
3. What are the key features of network programming? Discuss its scope in modern applications.  

### **2. Internet Addresses**  
1. Explain the `InetAddress` class in Java with an example. How can you check the reachability of an address?  
2. Differentiate between `Inet4Address` and `Inet6Address`. Provide code snippets for each.  
3. How can the `NetworkInterface` class be used to retrieve network interface information? Give an example.  

### **3. URLs and URIs**  
1. Differentiate between a URL and a URI with examples. How are relative URLs resolved?  
2. Explain the key methods of the `URL` class in Java for retrieving data and splitting URLs.  
3. How does Java handle password-protected sites using the `Authenticator` and `PasswordAuthentication` classes?  

### **4. HTTP**  
1. Explain the significance of the "Keep-Alive" feature in HTTP. How does it impact performance?  
2. Describe the common HTTP methods (GET, POST, PUT, DELETE) and their use cases.  
3. How are cookies managed in Java using `CookieManager` and `CookieStore`?  

### **5. URL Connections**  
1. Explain the process of reading data from a server using `URLConnection`. Provide a code example.  
2. How can you configure connection properties like timeouts and caching in `URLConnection`?  
3. What are the security considerations when using `URLConnection`?  

### **6. Socket for Clients**  
1. Explain the basic socket operations for client-server communication with an example.  
2. What are the key socket options (e.g., `TCP_NODELAY`, `SO_TIMEOUT`)? How do they affect performance?  
3. How can sockets be used in a GUI application? Provide a simple example.  

### **7. Socket for Servers**  
1. Explain how multithreaded server sockets work. Provide a code example.  
2. What are the key differences between client and server sockets in Java?  
3. How can you implement a simple HTTP server using Java sockets?  

### **8. Secure Socket**  
1. Explain how SSL/TLS works in secure socket communication.  
2. What are the steps to create a secure client socket in Java?  
3. How can you configure cipher suites in an SSL server socket?  

### **9. Nonblocking I/O**  
1. Explain the concept of buffers in Java NIO. How are they used in network programming?  
2. Differentiate between blocking and non-blocking I/O in socket programming.  
3. How does a `Selector` work in Java NIO? Explain with an example.  

### **10. UDP**  
1. Compare TCP and UDP protocols. When would you prefer UDP over TCP?  
2. Explain the `DatagramPacket` and `DatagramSocket` classes with an example.  
3. How can you implement a simple UDP echo client-server program?  

### **11. IP Multicast**  
1. What is IP multicasting? Explain multicast addresses and groups.  
2. How does Java support multicasting using `MulticastSocket`? Provide an example.  
3. What are the challenges in multicast routing?  

### **12. Remote Method Invocation (RMI)**  
1. Explain the architecture of Java RMI with a diagram.  
2. What are the steps to create an RMI server and client in Java?  
3. How does RMI differ from web services?  

----

## 10 Marks Questions

### **1. Introduction**  
1. **Explain the client-server model in detail.** Discuss its advantages and disadvantages compared to peer-to-peer (P2P) architecture. Provide real-world examples where each model is preferred. *(5 marks for explanation, 3 marks for comparison, 2 marks for examples)*  

2. **Discuss the role of different programming languages (Java, Python, C) in network programming.** Compare their features, libraries, and suitability for developing client-server applications. *(4 marks for features, 4 marks for comparison, 2 marks for suitability analysis)*  

---

### **2. Internet Addresses**  
1. **Explain the `InetAddress` class in Java with its key methods.** Write a Java program to retrieve and display the IP address of a given hostname. Also, discuss how `Inet4Address` and `Inet6Address` differ. *(5 marks for explanation, 3 marks for code, 2 marks for differences)*  

2. **What is the purpose of the `NetworkInterface` class?** Write a Java program to list all network interfaces along with their IP addresses. How can this be useful in network diagnostics? *(4 marks for explanation, 4 marks for code, 2 marks for use case)*  

---

### **3. URLs and URIs**  
1. **Differentiate between URI, URL, and URN with examples.** Explain how relative URLs are resolved in Java using the `URI` class. Provide a code example demonstrating URL encoding and decoding. *(4 marks for differences, 3 marks for resolution, 3 marks for code)*  

2. **How does Java handle password-protected websites?** Explain the `Authenticator` and `PasswordAuthentication` classes with a code example. Also, discuss the security implications of storing passwords in applications. *(5 marks for explanation, 3 marks for code, 2 marks for security discussion)*  

---

### **4. HTTP**  
1. **Explain the HTTP protocol, including methods (GET, POST, PUT, DELETE) and headers.** How does the "Keep-Alive" mechanism improve performance? Provide a Java example demonstrating HTTP GET request handling. *(4 marks for protocol, 3 marks for Keep-Alive, 3 marks for code)*  

2. **Discuss cookie management in Java using `CookieManager` and `CookieStore`.** Write a program to handle cookies while accessing a website. Why are cookies important in web sessions? *(5 marks for explanation, 3 marks for code, 2 marks for importance)*  

---

### **5. URL Connections**  
1. **Explain the working of `URLConnection` in Java.** How can you read headers, set timeouts, and handle caching? Provide a complete example demonstrating data retrieval from a web server. *(5 marks for explanation, 3 marks for code, 2 marks for timeout/caching discussion)*  

2. **What are the security risks associated with `URLConnection`?** Discuss how to mitigate these risks while accessing sensitive data. Provide a code example for secure data fetching. *(5 marks for risks, 3 marks for mitigation, 2 marks for code)*  

---

### **6. Socket for Clients**  
1. **Explain socket programming in Java for client-server communication.** Write a complete TCP client program that connects to a server, sends a message, and receives a response. Discuss key socket options (`SO_TIMEOUT`, `TCP_NODELAY`). *(5 marks for explanation, 3 marks for code, 2 marks for socket options)*  

2. **How can sockets be integrated into a GUI application?** Develop a simple chat client using Java Swing and sockets. Explain the challenges of multithreading in such applications. *(4 marks for GUI integration, 4 marks for code, 2 marks for challenges)*  

---

### **7. Socket for Servers**  
1. **Explain multithreaded server socket programming in Java.** Write a server program that handles multiple clients concurrently. Discuss the importance of logging in server applications. *(5 marks for explanation, 3 marks for code, 2 marks for logging)*  

2. **How can you implement an HTTP server using Java sockets?** Develop a simple server that responds to GET requests with a static webpage. Compare it with a full-fledged server like Apache. *(5 marks for implementation, 3 marks for code, 2 marks for comparison)*  

---

### **8. Secure Socket**  
1. **Explain SSL/TLS in Java secure socket programming.** Write a program for a secure client-server communication using `SSLSocket`. How does certificate validation work? *(5 marks for explanation, 3 marks for code, 2 marks for certificates)*  

2. **Discuss session management in secure sockets.** How can you configure cipher suites for an SSL server? Provide a code example. *(5 marks for session management, 3 marks for cipher suites, 2 marks for code)*  

---

### **9. Nonblocking I/O**  
1. **Compare blocking I/O with non-blocking I/O in Java NIO.** Explain `Selector`, `Buffer`, and `Channel` with an example of a non-blocking echo server. *(5 marks for comparison, 3 marks for explanation, 2 marks for code)*  

2. **How does `ByteBuffer` work in Java NIO?** Discuss its key methods (`flip()`, `compact()`, `put()`, `get()`). Write a program demonstrating bulk data transfer using channels. *(5 marks for explanation, 3 marks for code, 2 marks for bulk transfer)*  

---

### **10. UDP**  
1. **Compare TCP and UDP protocols.** Write a UDP client-server program in Java for a simple messaging system. Discuss reliability issues in UDP. *(5 marks for comparison, 3 marks for code, 2 marks for reliability)*  

2. **Explain multicast sockets in Java.** Write a program where a server sends messages to multiple clients using multicast. What are the challenges in multicast routing? *(5 marks for explanation, 3 marks for code, 2 marks for challenges)*  

---

### **11. IP Multicast**  
1. **What is IP multicasting?** Explain multicast addressing and groups. Write a Java program to demonstrate a simple multicast chat application. *(5 marks for explanation, 3 marks for code, 2 marks for addressing)*  

2. **How do routers handle multicast traffic?** Discuss the role of IGMP (Internet Group Management Protocol) in multicast communication. *(6 marks for router handling, 4 marks for IGMP)*  

---

### **12. Remote Method Invocation (RMI)**  
1. **Explain the RMI architecture in Java.** Write a complete RMI program where a client invokes a remote method to perform a calculation. *(6 marks for architecture, 4 marks for code)*  

2. **Compare RMI with web services (REST/SOAP).** When would you prefer RMI over REST, and vice versa? *(5 marks for comparison, 5 marks for use cases)*  

---
