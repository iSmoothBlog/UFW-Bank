# UFW Application
Enhance firewall with perfect application profiles.

## Enable Applications
* Apache (Web Server)
* NGINX (Web Server)
* OpenSSH (Secure Shell)
* Dovecot (Mail Management)
* Postfix (Mail Submission)
* OdooERP (Odoo Server)

And many more, any other alternative for these applications should work.

## Installation
Clone this repository into your system and install the required files:

```
git clone https://github.com/iSmoothBlog/UFWApp.git
cd UFWApp
sudo make install
```

## Usage
Exchange `*` with a selected profile:

* Web Server
* Secure Shell
* Mail Submission
* Mail Management
* File Transfer
* Odoo Server

```
ufw allow "*"
```

A profile selected should work for all applications in the same field.

## Learn More
Find more information about UFWApp on [iSmoothBlog](http://www.ismoothblog.com).
