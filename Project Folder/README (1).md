<picture><source media="(prefers-color-scheme: dark)" srcset="https://nextwork.ai/static/nextwork-logo-paper.svg" /><img src="https://nextwork.ai/static/nextwork-logo-leather.svg" alt="NextWork" width="300" /></picture>

# Build a Virtual Private Cloud

**Project Link:** [View Project](https://nextwork.ai/projects/c6fbf52f-0759-4ff2-b673-d2ad921973f5)

**Author:** K . aditya Kumar

---

## Introducing Today's Project!

In this project, I will demonstrate... I'm doing this project to learn AWS

## Virtual Private Clouds (VPCs)

### What I did in this step

In this step, I will... because...\
Access the VPC console in AWS.\
Create a VPC.

### How VPCs work

VPCs are the reason why resources can be made private to you. You also get control over resources in a VPC, so you can organize how they communicate and integrate with each other without the public internet.

### Why there is a default VPC in AWS accounts

There was already a default VPC in my account ever since my AWS account was created. This default VPC is why you could launch resources (e.g. EC2 instances) and connect services together from Day 1 of using AWS. If it didn't exist, you would've had to learn how to create a VPC before you can use some of the services that need VPCs to function.

![Virtual Private Clouds (VPCs)](https://nextwork.ai/k-kumar/uploads/c6fbf52f-0759-4ff2-b673-d2ad921973f5_2facf927)

### Defining IPv4 CIDR blocks

To set up my VPC, I had to define an IPv4 CIDR block, which is...

## Subnets

### What I did in this step

In this step, I will... because...

### Creating and configuring subnets

Subnets are... There are already subnets existing in my account, one for every...

### Public vs private subnets

The difference between public and private subnets are... For a subnet to be considered public, it has to...\
A public subnet is connected to the internet 🌐 Resources inside a public subnet can communicate with external networks.

A private subnet does not have direct internet access 🔐 You'd use it for internal resources that don’t need to be publicly accessible.

![Subnets](https://nextwork.ai/k-kumar/uploads/c6fbf52f-0759-4ff2-b673-d2ad921973f5_157c4219)

### Auto-assigning public IPv4 addresses

By default, your resources already have private IP addresss, but this only allows internal communication within your VPC.To access the internet or be accessible from the internet, the instance would need a public IP address.

When you enable auto-assign public IPv4 address for a subnet, any EC2 instance launched in that subnet will instantly get a public IP address so you won't have to create one manually - a huge time saver!
