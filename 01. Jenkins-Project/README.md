## _Jenkins Introduction_

### _Java Installation_
![](./img/1.%20java-installation.png)
For jenkins server to run successfully, it's important to install java on the linux machine. "OpenJDK JDK / JRE 17 - 64 bits" was installed using the commands below;
sudo apt update
sudo apt install fontconfig openjdk-17-jre

### _Jenkins server installation_
![](./img/2.%20jenkins-installation.png)
jenkins server was successfully installed using the commands provided in the manual/guide.

### _Jenkins first-time page_
![](./img/3.%20jenkins-page.png)
In the security settings of the EC2 instance, port 8080 was open to 0.0.0.0/0 so as to callup jenkins using http://184.73.18.231:8080/

### _Admin password_
![](./img/4.%20jenkins-admin-password.png)
The command "cat & the path" provided will give us the admin password as seen in the image.

### _Install customize plugins_
![](./img/5.%20jenkins-customize-page.png)

### _Jenkins is ready_
![](./img/6.%20jenkins-ready.png)

### _Jenkins dashboard_
![](./img/7.%20jenkins-dashboard.png)

I have been able to master how to successfully install jenkins server.

Thank you