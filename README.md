# DevOps_experiments
1) Host a dummy webpage using apache web server - Ubuntu
```
sudo apt-get install apache2
```
- Once installation is completed open "localhost" OR "127.0.0.1" in your browser >> You should see "Apache2 Ubuntu Default Page"
- Alternatively you can find your eth0 IP address by invoking 
```
ipconfig
```
- Enter etho0 IP address in browser and check if you can see "Apache2 Ubuntu Default Page"
- You can also verify if you are running an instance of apache on port 80 by invoking
```
netstat -an | more
```
- Adding a webpage
```
cd /var/www/html
```
- You can find default index.html inside and the contents can be modified as per your requirements.
