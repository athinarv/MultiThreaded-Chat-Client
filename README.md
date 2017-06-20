# MultiThreaded-Chat-Client
1. Socket Example:
- ChatServer.java (Simulated Socket operation in server side)
- MultiThreadChatClient.java (Simulated Socket operation in client side)

-compile steps:
   - open one command window:
   Compile 
   - input: javac Server.java
   - input: java Server
   - open another command window
   Compile
   - input javac HostInfo.java (to see your host IP address)
   - input java HostInfo
   Compile
   - input: javac MultiThreadChatClient.java
   - input: java MultiThreadChatClient [ipaddress of server side]
        - Input the IP Adress previously obtained
        - Input username desired
        - Enter message
   
 2. Second Client Example:
 - open another window:
 Already Compiled
 - input: java HostInfo
 - input: java MultiThreadChatClient
    - IP Adress
    - Choose username desired
    - Enter message
   
3. Host Information Example:
- HostInformation.java

 -compile steps:
   - open one command window:
   - input: javac HostInfo.java
   - input: java HostInfo
