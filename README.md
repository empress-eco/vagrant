<div align="center">
![Project Logo](https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png
</div>

# Vagrant: Unleash Your Virtual Development Environment

Vagrant is an incredible tool designed to simplify the setup and management of virtual development environments, providing a flexible, convenient solution for developers and teams looking to streamline their workflow and maintain consistent environments.

- [Explore the Docs](https://empress.eco/)
- [Report Bug](https://github.com/empress-eco/vagrant/issues)
- [Request Feature](https://github.com/empress-eco/vagrant/issues)

## About The Project

### Overview
Vagrant empowers you to set up and manage your virtual development environment effortlessly. It's ideal for developers seeking to optimize their workflow and teams aiming to maintain consistent development environments across different workstations.

### Key Features
- Effortless setup of virtual development environments.
- Consistent environments across teams, ensuring smooth collaboration.
- Compatibility with multiple virtualization platforms for increased flexibility.

### Built With
This project leverages the power of:
- [VirtualBox](https://www.virtualbox.org/)
- [Vagrant](https://www.vagrantup.com/)

## Getting Started

### Prerequisites
Ensure you have the following installed before starting:
- VirtualBox
- Vagrant for Windows
- GitHub Desktop for Windows
- Git Shell 

### Installation
Setting up a Vagrant development environment is as easy as following these steps:

```sh
# Clone this repo into a local folder
git clone https://github.com/empress-eco/vagrant.git vagrant

# Start your virtual machine
vagrant up

# Connect to your guest system via SSH
vagrant ssh

# Set "developer_mode": 1 in /vagrant/Empress-bench/sites/site1.local/site_config.json
vim /vagrant/Empress-bench/sites/site1.local/site_config.json

# Navigate to your Empress-bench folder and start bench
cd /vagrant/Empress-bench/
bench start

# Access your Empress by browsing to http://localhost:8080/ or http://127.0.0.1:8080 on your host system browser
```

## Usage
Vagrant is used for setting up and managing a virtual development environment. It offers an easy way to access and manage your environment through the command line.

## Contributing
We encourage and welcome contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. Your contributions are also licensed under the same.

## Acknowledgements

We want to express our deepest gratitude to the Empress Community, whose innovative and dedicated work has been instrumental in building the fundamental tools that power this project. We are profoundly grateful for their pioneering work and ongoing support.

<!-- MARKDOWN LINKS & IMAGES -->