# HybridCloudEngineer_Project3
Project 3 of the Nutanix Hybrid Cloud Engineer Nanodegree
Using Nutanix Calm to create reusable Blueprints for automated CI/CD operations.
This project uses Nutanix on-prem, private cloud, integrated with AWS off-prem, public cloud, to automated Application deployment.
Business Stakeholder Requirements for this 
three tier web application are:

a load balancer,
a web server,
and a database server.
Developers need two sizes of deployment scenarios (small and medium), the ability to scale in and scale out the web tier independently on each provider, and to perform a database backup and restoral at any time.
Design a blueprint to deploy and configure a three tier web application with a load balancer hosted on the private cloud, two web server tiers (each hosted on a private and a public cloud), and database VM hosted on the public cloud.
Insure each VM in configured with the proper resources and tasks
Test the deployment works with a read and write to the database.
Test web tier scaling: scale-in and scale-out actions changing the population by a count of 1 on private cloud separately from scaling on the public cloud.
Allow self-service, ad-hoc backup of the database.
Create two application profiles for deployment for a small (1 vCPU, 1 core, 1GB RAM or t2.micro) and medium (2vCPU, 2 cores, 1GB RAM or t2.micro) CPU and memory configuration variants.
