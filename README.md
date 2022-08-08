# docker-dnsmasq

### Usage

Simply build the container and spinn up your(``docker-compose up --build``) local install of apache or nginx or whatsover.

all of your local services will now listen to the TLD .test.

if you want to have a other TLD just add the required TLD to the dockerfile in bin/dns/dockerfile and add a new nameserver.

![image](https://user-images.githubusercontent.com/19891785/183496585-1b58907a-2e24-4c3a-abdb-2ea80af5920d.png)
