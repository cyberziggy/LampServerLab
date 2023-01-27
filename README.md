<h1>Lamp Server Lab</h1>



<h2>Description</h2>
The project involves using open-source tools to build a web application. A web application requires four key components: a server operating system, a web server, a database, and a programming language. These layers of software are essential for creating a website that is driven by a database and can display dynamic content.
<br />


<h2>Commands and Utilities Used</h2>

- <b>Oracle VM VirtualBox</b> 
- <b>Ubuntu Linux Version 22.04</b> 
- <b>User with Sudo Priveleges</b> 
- <b>Terminal/Command line</b>

<h2>Environments Used </h2>

- <b>Ubuntu Linux 22.04</b> 

<h2>Program walk-through:</h2>

<p align="center">
Install Apache(Before installing apache ensure that the package is on the system and up to date.:

 ![lamp1](https://i.imgur.com/uzChvys.png)

 <p align="center">
  Install the Apache package by running the following command:
  
  ![apache](https://i.imgur.com/p5nGrLr.png)
  
  
 <p align="center">
  Check if Apache is installed correctly by checking the service status (Should say "Active *running")
  
  ![active](https://i.imgur.com/9ac7WCF.png)
   
  <p align="center"> "exit screen with Ctrl+C"
  
  <p align="center">
   Next make sure the UFW firewall contains Apache profiles typing this command "sudo ufw list"
   
   ![ufw](https://i.imgur.com/dnifB19.png)
   
   <p align="center">
    Make sure the Apache profile allows trafficce on ports 80 and 443 running the command *sudo ufw app info "Apache Full"*
    
    
   
   
   
   
   
  




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
