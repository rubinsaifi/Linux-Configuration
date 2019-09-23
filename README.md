# Linux Server Configuration
This project is a part of `Full Stack Web Developer Nanodegree` cource from Udacity

## Project Requirements
1. Setup Linux server using Amazon [Lightrail](https://lightsail.aws.amazon.com/) service
2. Checkout [Item-Catalog](https://github.com/rubinsaifi/Item-catalog.git) project code from Github
3. Modify Google OAUTH Settings
4. Host Item-Catalog application

## Submission Requirements
1. Creat a new GitHub repository
- Status: Completed. Repository [Link](https://github.com/rubinsaifi/Linux-Configuration.git)
2. Provide IP Address and Port number for review
- IP: 54.245.59.128
- SSH Ports: 22, 2222
- Project URL: 
3. Software used and configuration changes
```
- Modified /etc/ssh/sshd_config to allow ssh connections on Port 22 and 2222
- Denied Empty Passwords
- Denied Password based logins (SSH to only allow connection via PEM file)
- Install git package
-- sudo apt-get install git
- User 'grader' created and access ristricted via PEM file
- No additional packages installed apart from Item-Catalog requirements
 ```
 
 
