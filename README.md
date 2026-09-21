<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Build a Virtual Private Cloud

**Project Link:** [View Project](https://nextwork.ai/projects/7f907ac7-2473-5c15-a8be-edb36581cdba)

**Author:** Ahmed Umar Rehman  
**Email:** ahmedumar475@gmail.com

---

![Image](https://nextwork.ai/calm_indigo_beautiful_lizard/uploads/7f907ac7-2473-5c15-a8be-edb36581cdba_2facf927)

## Introducing Today's Project!

In this project, I will demonstrate how to make Amazon VPC I'm doing this project to learn how subnets work and how security measures work.

## Virtual Private Clouds (VPCs)

### What I did in this step

In this step, I will create VPC because, I want to see how subnets work and security group 

### How VPCs work

VPCs are like private city in country filled with many resources which you can make in oder to secure them.

### Why there is a default VPC in AWS accounts

There was already a default VPC in my account ever since my AWS account was created. This is because If it didn't exist, you would've had to learn how to create a VPC before you can use some of the services that need VPCs to function.

![Image](https://nextwork.ai/calm_indigo_beautiful_lizard/uploads/7f907ac7-2473-5c15-a8be-edb36581cdba_2facf927)

### Defining IPv4 CIDR blocks

To set up my VPC, I had to define an IPv4 CIDR block, which is 10.0.0.0/16

## Subnets

### What I did in this step

In this step, I will create subnet because I want to see where different resources will live and operate.

### Creating and configuring subnets

Subnets are like connecting resources through neighbourhood. There are already subnets existing in my account, one for every AZ

### Public vs private subnets

The difference between public and private subnets are public for internet and private for internal resources. For a subnet to be considered public, it has to Have a route to an Internet Gateway (IGW) in its route table.

![Image](https://nextwork.ai/calm_indigo_beautiful_lizard/uploads/7f907ac7-2473-5c15-a8be-edb36581cdba_157c4219)

### Auto-assigning public IPv4 addresses

Once I created my subnet, I enabled auto assign IPv4 address. that instances launched in the subnet automatically receive a public IPv4 address so they can communicate with the internet.

## Internet gateways

### What I did in this step

In this step, I will Connect your VPC to the internet using a internet gateway. because it allows resources in my VPC to communicate with the internet.

### Setting up internet gateways

Internet gateways connects your city (VPC) and the outside world (internet).

Attaching an Internet Gateway to a VPC means the VPC has a gateway that can provide a path for internet traffic.

If I missed this step: resources in the VPC would not be able to communicate with the internet through an Internet Gateway.

![Image](https://nextwork.ai/calm_indigo_beautiful_lizard/uploads/7f907ac7-2473-5c15-a8be-edb36581cdba_4ae90410)

## Using the AWS CLI

### What I'm doing in this extension

In this project extension, I will Launch a VPC in Seconds with AWS CloudShell

### Exploring CloudShell and CLI

CLI is a Command Line Interface — it lets you create and manage AWS resources by typing commands instead of using the AWS Console.

### Debugging my setup

To set up a VPC or a subnet, you can use the command aws ec2 create-subnet --vpc-id VPC-ID --cidr-block ADD-CIDR-BLOCK-HERE. Make sure to avoid errors by including the correct VPC ID and a valid CIDR block.

![Image](https://nextwork.ai/calm_indigo_beautiful_lizard/uploads/7f907ac7-2473-5c15-a8be-edb36581cdba_9b2465411)

### Comparing CloudShell vs AWS Console

Compared to using the AWS Console, an advantage of using commands is that commands are faster and can be repeated easily. An advantage of using the Console is that it provides a visual interface that makes it easier to understand and configure resources. Overall, I preferred using the Console because it was easier for me to understand the VPC setup.

---

*Built with [NextWork](https://nextwork.ai) - [View this project](https://nextwork.ai/projects/7f907ac7-2473-5c15-a8be-edb36581cdba)*
