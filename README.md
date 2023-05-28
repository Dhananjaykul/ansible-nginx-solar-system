
# Ansible Nginx Solar System Deployment 🚀🌍

This repository contains the code and playbook for automating the deployment of Nginx and a captivating solar system-themed webpage using Ansible.

## Prerequisites ✅

Before running the playbook, ensure that you have the following:

- Ansible installed on your local machine or Ansible control node.
- SSH access to the target EC2 instances.
- AWS credentials and access to create and manage EC2 instances.

## Getting Started 🚀

Follow these steps to deploy Nginx and the solar system webpage using Ansible:

1. Clone this repository to your local machine.
2. Update the inventory file (`/etc/ansible/hosts`) with the IP addresses or hostnames of your target EC2 instances.
3. Edit the `nginx-playbook.yml` file to customize any variables or settings according to your requirements.
4. Ensure that your private key is located at the correct path on your Ansible control node (`/home/ubuntu/.ssh`).
5. Run the following command to execute the playbook:

```shell
ansible-playbook nginx-playbook.yml
```

6. Ansible will connect to the target EC2 instances, install Nginx, and deploy the solar system webpage.
7. Once the playbook execution is complete, you can access the webpage by entering the IP addresses or hostnames of the EC2 instances in a web browser. 🌐

For more detailed instructions and insights, refer to the accompanying [blog post](https://dhananjaykulkarni.hashnode.dev/ansible-project-automating-infrastructure-deployment) on Hashnode. 📖

## File Structure 📁

- `nginx-playbook.yml`: Ansible playbook file for installing Nginx and deploying the solar system webpage.
- `index.html`: HTML file for the captivating solar system webpage.

## Contributing 🤝

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request. 🙌
```
