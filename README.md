# terraform

Initialize the project, which downloads a plugin that allows Terraform to interact with Docker.

terraform init

Provision the NGINX server container with apply. When Terraform asks you to confirm, type yes and press ENTER.

terraform apply

Verify NGINX instance
Run docker ps to view the NGINX container running in Docker via Terraform.

docker ps
