# Terraform Docker Task

This project provisions a Docker container running an Nginx web server using Terraform on a local machine.

## 📦 What It Does

- Pulls the `nginx:latest` Docker image.
- Creates a Docker container named `nginx-server`.
- Maps port `8080` on your local machine to port `80` in the container.

## 📂 Files

- `main.tf` – Contains all Terraform configuration to provision Docker resources.
- `.gitignore` – Excludes Terraform and system-specific files.

## 🚀 How to Use

1. **Install Requirements**  
   - [Terraform](https://developer.hashicorp.com/terraform/downloads)  
   - [Docker Desktop](https://www.docker.com/products/docker-desktop/)

2. **Clone the repo**
   ```bash
   git clone https://github.com/Ushareddy1310/terraform-docker-task.git
   cd terraform-docker-task
3. **Initialize Terraform**

    Run the following command to initialize the Terraform working directory. This will download the necessary provider plugins and prepare your environment:

   ```bash
   terraform init
4. **Create an Execution Plan** 

   Generate and review the execution plan with this command. Terraform will show you what actions it will perform on your infrastructure:

   ```bash
   terraform plan
5. **Apply the Terraform Configuration**

   Apply the changes required to reach the desired state of the configuration. Terraform will prompt you to confirm before making any changes:

   ```bash
   terraform apply
6. **Verify the Docker Container**

   After applying the Terraform configuration, verify that the Docker container is running by executing:

     ```bash
     docker ps
    
**✅ Confirm the Nginx Server is Running**

Open your browser and visit:
http://localhost:8080

You should see the default Nginx welcome page, confirming that the container is up and running successfully.

















  


