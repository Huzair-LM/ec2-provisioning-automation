## 🚀 EC2 Provisioning Script (Bash)

This Bash script automates the launch of an Amazon EC2 instance using the AWS CLI. It’s my first design for my DevOps roadmap (phase 1), which covers automation and covers how to streamline infrastructure setup and build hands-on AWS experience via the aws dashboard. Tools used were:
-Git Bash
-Python 3.13
-VS Code
-AWS CLI
-windows powershell/CLI

### 🔧 Features

- **Automated EC2 Launch**: Spins up an instance with your chosen AMI, instance type, key pair, and security group.
- **Tagging Support**: Adds a custom tag to help identify your instance.
- **Public IP Retrieval**: Extracts and displays the instance’s public IP.
- **Clipboard Integration**: Automatically copies the IP to your clipboard (supports macOS, Linux, and Windows).
- **Cross-Platform Friendly**: Works in Git Bash, WSL, or native Linux/macOS terminals.
- **Error Handling**: Gracefully handles missing dependencies or AWS CLI misconfigurations.

### 🧠 Why It Matters

This script helps you:
- Eliminate repetitive manual steps in EC2 provisioning.
- Practice real-world CLI automation and scripting.
- Build a foundation for Infrastructure as Code (IaC) workflows.
- Save time and reduce human error when testing or deploying cloud resources.
- Routine automation helps build muscle memory in the processes used in everyday Dev Ops environments

### 📁 Example Usage

```bash
bash launch-ec2.sh
