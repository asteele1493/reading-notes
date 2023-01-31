# AWS: Cloud Servers

[AWS EC2](https://aws.amazon.com/ec2/)

**What is an EC2 Instance?**

- An EC2 instance is tailored to fit different use cases, but generally provide a balance of compute, memory, and networking resources that can be used for diverse workloads. Instances can be tailored to fit differing scales or optimizations.

**Name 2 use cases for EC2.**

- Real time big data analytics
- Application development environments

**Provide 1 reason to use EC2 instead of a service such as Heroku, Digital Ocean, or Render.com.**

- EC2 can be tailored to fit applications of varied needs. It's easier to scale and optimize specific needs as they develop over time.

[EC2 for Humans](https://www.youtube.com/watch?v=lZMkgOMYYIg)

**Where can we find EC2 on the AWS Console?**

- Under the 'compute' section. You can also use the AWS services search bar to find the EC2 page.

**Explain the general difference between T2 Micro and XL.**

- T2 micro instances are accessible to use through AWS' free tier. They are smaller instances that can dramatically reduce costs for applications. XL instances, I believe, are used for high networking, high volume applications. They typically have more memory, more CPU, more bandwidth than other instance types/sizes.

**Explain a “Compute Cycle” to a non-technical friend.**

- When you launch an EC2 instance, it triggers the life cycle of the instance. This cycle encompasses different states including 'pending' meaning the instance isn't fully to it's running state. 'Running', which means the instance is ready for use; to 'stopping' which transitions to 'stop'-- I feel like that part is pretty explanatory. And then the instance could either transition back to pending and run OR to shutting-down and terminated to complete/end the cycle.

[Diagram](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-lifecycle.html)

[Elastic Beanstalk](https://www.youtube.com/watch?v=SrwxAScdyT0)

**What is Elastic Beanstalk?**

- Elastic Beanstalk is an AWS service that deploys, manages, and scales web applications and services.

**Describe the relationship between EC2 and Elastic Beanstalk.**

- Elastic Beanstalk helps manage EC2 instances. In other words, the two work in conjunction to manage, scale, and deploy applications.

**Name some benefits of using Elastic Beanstalk.**

- Elastic Beanstalk saves time when it comes to managing/configuring server settings.

- Helps automate other AWS services such as EC2

- When configuring Elastic Beanstalk, there are many configurations and customizations you can choose to truly tailor your application.

## Bookmark & Review

[Virtual Machines](https://www.youtube.com/watch?v=yIVXjl4SwVo)