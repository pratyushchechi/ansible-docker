# Ansible-Managed Docker Services

This project demonstrates how to use Ansible to deploy and manage Docker services like Nginx and Redis on an AWS EC2 instance.

## Project Structure

- `ansible/`: Contains Ansible playbooks for installing Docker, and deploying Nginx and Redis.
- `docs/`: Contains detailed project documentation.

## How to Use

1. Clone the repository.
2. Navigate to the `ansible/` directory and run the playbooks in the desired order.

## Playbooks

- `install_docker.yml`: Installs Docker on the EC2 instance.
- `deploy_nginx.yml`: Deploys Nginx as a Docker container.
- `deploy_redis.yml`: Deploys Redis as a Docker container.

For detailed documentation, please refer to the `docs/` directory.

