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
STEP 1 Install Apache(Before installing apache ensure that the package is on the system and up to date.:

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
    
   ![a2](https://i.imgur.com/NKO94zn.png)
    
 Confirm that Apache is running by typing the IP address of the server in your adddress bar on the internet browser
     
   ![ip](https://i.imgur.com/CC4QRlz.png)
   
<p align="center">
 STEP 2 Install MYSQL with this command "sudo apt install mysql-server -y" 
 
 ![mysql](https://i.imgur.com/nMVq3nR.png)
 
 <p align="center">
  STEP 3 Install PHP with this command "sudo apt install php libapache2-mod-php php-mysql -y"
  
  ![php](https://i.imgur.com/2jssa9k.png)
  
  <p align="center">
   Modify the way Apache serves files opening the "dir.conf" file in text editor with root privileges
   "sudo nano /etc/apache2/mods-enabled/dir.conf" the configuration file should look like this... edit the file so that the "index.php" is the first option
   
   ![config](https://i.imgur.com/wFKf6Hz.png)
   
   <p align="center">
   Install PHP Tidy "PHP Tidy is a built-in extension in PHP that allows developers to clean up and format their HTML, XHTML, and XML code. It can correct and reorder the HTML and XML tags, as well as adding missing tags and attributes."
    
   ![tid](https://i.imgur.com/yLlUxR9.png)
    
   <p align="center">
   STEP 4 Restart apache with the command "sudo systemctl restart apache2"
    
   <p align="center">
   STEP 5 TEST PHP processing on web server
     
   ![test](https://i.imgur.com/moSd0XQ.png)
   <p align="center"> Create a file in the web root directory with the command above
    
   <p align="center">
   Inside the file type 
    
   ![cod](https://i.imgur.com/8qvZL98.png)
    
    
    
    
    
    
    
   
   
   
   
  
  
 
 
    
    
    
    
   
   
   
   
   
  




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
