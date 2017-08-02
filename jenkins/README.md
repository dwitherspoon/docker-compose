# Jenkins

## NGINX
NGINX supports the proxy for all request coming into localhost on port 80 and forwards that to the Jenkins Master server on port 8080.  This will allow the ability in the future to support load balancing across the system.

In order to access Jenkins you will want to use the following URL:

```
http://localhost
```

## Login Credentials
These values depend on what you have assigned during the setup process.

```
username: jenkins
password: jenkins
```