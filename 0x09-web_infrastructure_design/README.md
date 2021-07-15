# 0x09. Web infrastructure design

## Learning Objectives

- You must be able to draw a diagram covering the web stack you built with the sysadmin/devops track projects  
- You must be able to explain what each component is doing  
- You must be able to explain system redundancy  
- Know all the mentioned acronyms: LAMP, SPOF, QPS  

## Tasks

### 0. Simple web stack

Design a one server web infrastructure that hosts the website that is reachable via `www.foobar.com`.  
Start your explanation by having a user wanting to access your website.  

You must use:  
- 1 server  
- 1 web server (Nginx)  
- 1 application server  
- 1 application files (your code base)  
- 1 database (MySQL)  
- 1 domain name foobar.com configured with a www record that points to your server IP 8.8.8.8  
<br>
<div align=center>  
    <img  
    style="text-align:center"  
    src="https://i.imgur.com/iJKoxCx.png"  
    alt="Distributed web infrastructure"/>  
</div>
