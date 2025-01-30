<p align="center">
  <img src="assets/diagram.png" 
</p>
  
## ☁️ 30 Days DevOps Challenge - Building a Containerized Soccer Stats App  ☁️

This is part of the sixth project of the 30-days DevOps Challenge! 

In this project we will be fetching Soccer sports API data from a Python application which will be wrapped up nicely as a Docker container! This part of the challenge outlines the learning process of working with microservices and containers.


<h2>Environments and Technologies Used</h2>

  - Docker
  - Amazon Web Services
  - Github Codespaces
  - Python
  - RapidAPI
  
  
<h2>Features</h2>  




<h2>Step by Step Instructions</h2>

***1. Repo configuration***


NOTE: Keep in mind this is for a Linux environment, check the AWS documentation to install it in your supported OS.


   curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install


We then do `AWS configure` and enter our access and secret key along with the region. Output format set to JSON. With this command we will double check that our credentials are put in place for CLI:

```
aws sts get-caller-identity
```

We will then roceed with installing the Docker CLI and Docker in Docker (Github Codespaces Setup)

```
curl -fsSL https://download.docker.com/linux/static/stable/x86_64/docker-20.10.9.tgz -o docker.tgz \
tar -xzf docker.tgz \
sudo mv docker/docker /usr/local/bin/ \
rm -rf docker docker.tgz
```

`Ctrl + p` on Github Codespace > `Add Dev Container Conf files` > modify your active configuration > click on Docker (Docker-in-Docker)

![image](/assets/image1.png)
```


***2. Terraform Configuration***



***3. Final Result***



<h2>Conclusion</h2>

In this project, I learned how to leverage terraform to automate creation of AWS services in preparation with the other projects in the multicloud bootcamp!
