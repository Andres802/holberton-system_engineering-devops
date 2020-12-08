<p align="center">
  <img src="https://www.holbertonschool.com/holberton-logo.png" width="360"/>
    <br>

<h1 align="center">System engineering & DevOps - Security</h1>
<h2 align="center">0x0B. SSH</h2>

---

<p align="center"> <img src="https://www.hostinger.com/tutorials/wp-content/uploads/sites/2/2017/07/ssh-client-and-server.jpg" width="500"/> </p>

---

## Resources:books:
Read or watch:
* [What is a (physical) server - text](https://intranet.hbtn.io/rltoken/PXE-o9DWronMp4ETwADOpg)
* [What is a (physical) server - video](https://intranet.hbtn.io/rltoken/IfLc3lxSs4w5xdsFlRDPWw)
* [SSH essentials](https://intranet.hbtn.io/rltoken/qKJi0RXLqaCLkHLCLhiYNA)
* [SSH Config File](https://intranet.hbtn.io/rltoken/DNiFD9w9Gx0mnQk5nXbtjg)
* [Public Key Authentication for SSH](https://intranet.hbtn.io/rltoken/ZBYjVLcJ-ck-CFjndgSDBw)
* [How Secure Shell Works](https://intranet.hbtn.io/rltoken/SW2m2e0KMA2K1dXk_0M0CA)
* [SSH Crash Course](https://intranet.hbtn.io/rltoken/8N-RlUma9lwGfyZp1_C-Wg)

---
## Learning Objectives:bulb:
What you should learn from this project:

* What is a server
* Where servers usually live
* What is SSH
* How to create an SSH RSA key pair
* How to connect to a remote host using an SSH RSA key pair
* The advantage of using  #!/usr/bin/env bash instead of /bin/bash

---

### [0. Use a private key](./0-use_a_private_key)
* Write a Bash script that uses ssh to connect to your server using the private key ~/.ssh/holberton with the user ubuntu.


### [1. Create an SSH key pair](./1-create_ssh_key_pair)
* Write a Bash script that creates an RSA key pair.


### [2. Client configuration file](./2-ssh_config)
* Your Ubuntu Vagrant machine has an SSH configuration file for the local SSH client, let’s configure it to our needs so that you can connect to a server without typing a password.
Share your SSH client configuration in your answer file.


### [3. Let me in!](./4-puppet_ssh_config.pp)
* Now that you have successfully connected to your server, we would also like to join the party.


---

<p align="center">
    <h2 align="center">Made by, David Arias Fuentes</h2>
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