🚀 Terraform Task 3: Provision Docker Container
===============================================

📌 Objective
------------

Use Terraform to provision a local Docker container running an NGINX server.

🛠️ Tools Used
--------------

*   Terraform
*   Docker

📂 Files Included
-----------------

*   `main.tf` - Terraform configuration file

📋 Steps to Run
---------------

1.  Install Docker and Terraform on your machine
2.  Open a terminal and navigate to the project folder
3.  Run `terraform init` to initialize Terraform
4.  Run `terraform plan` to see the execution plan
5.  Run `terraform apply` and type `yes` to confirm
6.  Open your browser and go to [http://localhost:8080](http://localhost:8080) to view the NGINX server
7.  (Optional) Run `terraform destroy` to remove the container

🌐 Port Mapping
---------------

Container Port `80` is mapped to Host Port `8080`.

📸 Output
---------

*   NGINX container pulled and started successfully
*   Accessible at `http://localhost:8080`

⚠️ Notes
--------

*   The attribute `docker_image.nginx.latest` is deprecated. Use `docker_image.nginx.name` instead.

👤 Author
---------
   # Ayush Trivedi
