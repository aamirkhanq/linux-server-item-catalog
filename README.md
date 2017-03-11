This project deploys Item-Catalog project on a linux server. 

- The IP address is `35.160.128.245`
- It has port 2200 as its SSH port
- The hosted web application can be accessed at `http://35.160.128.245` or `http://35.160.128.245/index`
- To set up a Linux Server using Amazon AWS EC2 instance, I had to follow the following steps:
  1. Created user accounts and gave them sudo access. The ability to login remotely as root was disabled.
  2. Installed requisite software needed to run the application. This included Python modules `sqlalchemy`, `oauth2client`, `flask` and `pip` for installing all the other modules mentioned before it.
  3. Installed `PostgreSQL` server.
  4. Configured the firewall so as not to listen on all ports.
