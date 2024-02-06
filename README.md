#### A Weather-App to get the real-time temperature, Humidity, wind speed, etc. of a particular city using HTML, CSS, and JavaScript.

# Deploying this Application on AWS EC2 #
* Testing the project locally

## Clone this project
* git clone https://github.com/Manisha53/Weather-App.git

## Start the project
* VSCode Run

## Set up an AWS EC2 instance
* Create an IAM user & log to your AWS Console
* Access Type - Password
* Permissions - Admin
* Create an EC2 instance
* Select an OS image - Ubuntu
* Create a new key pair & download the .pem file
* Instance type - t2.micro
* Connecting to the instance using ssh - putty
* Configuring Ubuntu on a remote VM

## Updating the outdated packages and dependencies
* sudo apt update
* Install Git - Guide by DigitalOcean

## Deploying the project on AWS
* Clone this project in the remote VM
* git clone https://github.com/Manisha53/Weather-App.git

## Deploying the project on AWS
* sudo apt install apache2
* cp -r Weather-App/* /var/www/html/
* systemctl start apache2
* Launch the web server on the public IPv4 address of EC2


#### NOTE - We will have to edit the inbound rules in the security group of our EC2, to allow traffic from our particular port

##### The project is deployed on AWS 🎉



![image](https://user-images.githubusercontent.com/37845282/190328770-a710bf3b-bc93-422f-af36-e9d47f236e18.png)

![image](https://user-images.githubusercontent.com/37845282/190331944-f8f11876-0ec4-4ada-a739-10bb62ed46d3.png)

![image](https://user-images.githubusercontent.com/37845282/190332084-8eeb8549-fff0-45f9-befb-2303e31237e9.png)

![image](https://user-images.githubusercontent.com/37845282/190332120-6de00890-56f2-483e-91d6-887809581266.png)

![image](https://github.com/Manisha53/Weather-App/assets/37845282/a38811aa-f516-4691-ac68-71d0676448cc)



