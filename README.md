# Nginx


## What is Nginx?
<p>Nginx (pronounced as "engine-X") is a high-performance, open-source web server and reverse proxy server software. It is widely used for serving web content, handling incoming web requests, and load balancing across multiple servers. Nginx is known for its speed, efficiency, and scalability, making it a popular choice for powering websites and web applications.</p>

## What is web server?
<p>Web server is a software that runs on a computer and is responsible for serving web pages to clients on the internet or intranet. It listens to incoming requests from clients and returns responses based on the request received. The response could be an HTML page, an image, a video, or any other file that the client has requested.</p>

## What is reverse proxy?
<p>A reverse proxy is a server that sits in front of one or more backend servers and forwards client requests to them. The reverse proxy can also perform other tasks, such as caching content, load balancing traffic, and terminating SSL/TLS connections.</p> 

## Installing Nginx
- Step 1: Update the package database on the system
          <p>sudo apt update</p>
          <p>sudo apt install nginx</p> 

- Step 2: Verify the installation
	        <p>nginx -v</p>
 
- Step 3: Chexking the status of Nginx
	        <p>systemctl status nginx</p>
 
- Step 4: Launching the Nginx Service
	        <p>sudo systemctl start nginx</p>
 
- Step 5: To start Nginx when system starts
          <p>sudo systemctl enable nginx</p>
 
- Step 6: To stop the Nginx Service
          <p>sudo systemctl stop nginx</p>
 
- Step 7: To restart Nginx
	        <p>sudo systemctl restart nginx</p>
 
- Step 8: To check if nginx is running we can copy the public ip address and paste it in any web browser and we will get a simple web page of Nginx.
