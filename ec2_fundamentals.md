Explain why Amazon EC2 stands for "Elastic Compute Cloud." What does the word elastic specifically refer to in cloud architecture? The service allows for scaling compute resources up or down based on demand, helping to optimize costs by avoiding payment for unused resources.

Name and describe the four essential infrastructure features provided by EC2 that classify it as Infrastructure as a Service (IaaS). 
Configurable virtual machines.
Data storage via Elastic Block Store (EBS), allowing choices between HDD and SSD.
Load balancing, which distributes traffic across multiple instances to manage transaction volume efficiently.
Auto-scaling, which automatically adjusts infrastructure size based on traffic to maintain performance while managing costs.

Detail the billing model used by EC2. What happens to your costs when you scale down or shut down instances when demand decreases?
Pay-as-you-go Model: Users are billed only for the actual time instances are running, whether calculated in seconds or hours.

What is the process of bundling configuration commands into a script called?
User data or "bootstraping"

Under which specific user profile are User Data scripts executed?
The root user

How many times does a User Data script run during the lifecycle of an EC2 instance?
once during the initial instance boot
