p align="center">
  <img src="https://www.holbertonschool.com/holberton-logo.png" width="360"/>
    <br>

<h1 align="center">System engineering & DevOps - Web Stack</h1>
<h2 align="center">0x0C. Web server</h2>

---

<p align="center"> <img src="https://media.geeksforgeeks.org/wp-content/uploads/20190927155217/webserver.png" width="500"/> </p>

---

## Resources:books:
Read or watch:
* [How the web works](https://intranet.hbtn.io/rltoken/4tRRzyyETAySzU-bgNGLSw)
* [Nginx](https://intranet.hbtn.io/rltoken/H9OfhUnBDdxV-QQnIucMlA)
* [How to Configure Nginx](https://intranet.hbtn.io/rltoken/wePwmjbJDgJZO7YPvffWxQ)
* [Root and sub domain](https://intranet.hbtn.io/rltoken/qkpso3mgcpv3tPUhBrZBOA)
* [HTTP requests](https://intranet.hbtn.io/rltoken/C9s3U62JbiOAvn9WCoxKsA)
* [HTTP redirection](https://intranet.hbtn.io/rltoken/kI4vRQ6vc45Wfbdo3UD8Lw)
* [Not found HTTP response code](https://intranet.hbtn.io/rltoken/5UvC588x2hZR7dm6eRFPoQ)
* [Logs files on Linux](https://intranet.hbtn.io/rltoken/bkqQ72HZVAV65G8nB503Pw)

---
## Learning Objectives:bulb:
What you should learn from this project:

* What is the main role of a web server
* What is a child process
* Why web servers usually have a parent process and child processes
* What are the main HTTP requests

---

### [0. Transfer a file to your server](./0-transfer_file)
* Write a Bash script that transfers a file from our client to a server:


### [1. Install nginx web server](./1-install_nginx_web_server)
* Web servers are the piece of software generating and serving HTML pages, let’s install one!


### [2. Setup a domain name](./2-setup_a_domain_name)
* .TECH Domains is one of the top domain providers. They are known for the stability and quality of their DNS hosting solution. Holberton School partnered with .TECH Domains so that you can learn about DNS.


### [3. Redirection](./3-redirection)
* Configure your Nginx server so that /redirect_me is redirecting to another page.


### [4. Not found page 404](./4-not_found_page_404)
* Configure your Nginx server to have a custom 404 page that contains the string Ceci n'est pas une page.


### [5. Design a beautiful 404 page](./5-design_a_beautiful_404_page)
* Design a beautiful 404 page


### [6. Install Nginx web server (w/ Puppet)](./7-puppet_install_nginx_web_server.pp)
* Time to practice configuring your server with Puppet! Just as you did before, we’d like you to install and configure an Nginx server using Puppet instead of Bash. To save time and effort, you should also include resources in your manifest to perform a 301 redirect when querying /redirect_me.

---

<p align="center">
    <h2 align="center">Made by, Andres Felipe Barrera</h2>
      <p align="center">
        <a href="https://twitter.com/codesectest" target="_blank">
            <img alt="twitter_page" src="https://github.com/gedafu/readme-template/blob/master/images/twitter.png" style="float: center; margin-right: 10px" height="50" width="50">
        </a>
        <a href="https://www.linkedin.com/in/andresbpulido/" target="_blank">
            <img alt="linkedin_page" src="https://github.com/gedafu/readme-template/blob/master/images/linkedin.png" style="float: center; margin-right: 10px" height="50"  width="50">
        </a>
        <a href="https://medium.com/@andres.bpulido" target="_blank">
            <img alt="medium_page" src="https://github.com/gedafu/readme-template/blob/master/images/medium.png" style="float: center; margin-right: 10px" height="50" width="50">
        </a>
      </p>
</p>

<p align="center">
   <img src="https://www.holbertonschool.com/holberton-logo.png"
     alt="Flow chart"
     style="float: left; margin-right: 10px;">
</p>
<p align="center">
<b>Holberton School - Colombia<b><br>
</p>
<p align="center">
<b>December, 2020.<b>
</p>