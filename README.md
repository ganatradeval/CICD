Continuous Integration Continuous Deployment

Tools: Chef, Jenkins, AWS Services, GIT
Procedure: 
        -Chef Workstation+ Jenkins Server on EC2 instance. It manages whole integration process
        -Chef will manage creation of servers and maintanance of any perticular server.Let's say we have 100 servers then chef will identify server based on its attributes. No need to worry about ip addresses of servers to deploy
        -AWS S3 and EC2 are main services we are using to maintain builds and servers. Other services like IAM, Cloud Watch, Cloud front etc can also useful.
        -Git is for version control.
        
        In overall, this project will deploy the code on develpment/testing server just after developer commits the code on Git. The whole process of Developer to Production environment can be automated.
