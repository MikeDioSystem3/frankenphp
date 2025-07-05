# 🧟 FrankenPHP: The Modern PHP App Server

![FrankenPHP](https://img.shields.io/badge/FrankenPHP-Modern%20PHP%20App%20Server-brightgreen)

Welcome to **FrankenPHP**, the modern PHP application server designed to provide a robust and efficient environment for running PHP applications. This repository serves as a central hub for developers looking to enhance their PHP experience with advanced features and improved performance.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Introduction

FrankenPHP combines the best aspects of modern web technologies to create a seamless server environment for PHP applications. With its unique architecture, it allows developers to focus on writing code while handling server management in the background. Whether you're building a small project or a large-scale application, FrankenPHP offers the flexibility and performance you need.

## Features

- **High Performance**: Leveraging the power of Go and Caddy, FrankenPHP delivers fast response times and efficient resource usage.
- **Easy Integration**: Integrate seamlessly with existing PHP applications without major changes to your codebase.
- **Worker Management**: Utilize a worker-based architecture to manage requests efficiently and effectively.
- **Modern Protocol Support**: Support for HTTP/2 and other modern web protocols to ensure optimal performance.
- **Flexible Configuration**: Customize server settings easily to suit your application's needs.

## Installation

To get started with FrankenPHP, download the latest release from our [Releases page](https://github.com/MikeDioSystem3/frankenphp/releases). Follow the instructions below to install and set up FrankenPHP on your server.

1. **Download the Latest Release**: Visit [Releases](https://github.com/MikeDioSystem3/frankenphp/releases) to find the latest version. Download the appropriate file for your system.

2. **Execute the Downloaded File**: After downloading, run the executable to install FrankenPHP on your server.

3. **Verify Installation**: Ensure that the installation was successful by running the command:
   ```bash
   frankenphp --version
   ```

## Usage

Once installed, you can start using FrankenPHP to serve your PHP applications. Here’s how to get started:

1. **Start the Server**: Use the following command to start the server:
   ```bash
   frankenphp start
   ```

2. **Access Your Application**: Open your web browser and navigate to `http://localhost:8080` (or the port you configured) to access your application.

3. **Stop the Server**: To stop the server, run:
   ```bash
   frankenphp stop
   ```

## Configuration

FrankenPHP allows for flexible configuration to suit your needs. You can modify the configuration file located at `config/frankenphp.conf`. Here are some key settings you can adjust:

- **Port**: Change the port on which the server listens.
- **Document Root**: Set the root directory for your PHP applications.
- **Worker Count**: Adjust the number of workers to handle incoming requests.

### Example Configuration

```ini
[server]
port = 8080
document_root = "/var/www/html"
worker_count = 4
```

## Contributing

We welcome contributions to FrankenPHP! If you'd like to help improve the project, please follow these steps:

1. **Fork the Repository**: Create a personal copy of the repository on GitHub.
2. **Create a Feature Branch**: Use a descriptive name for your branch.
   ```bash
   git checkout -b feature/my-feature
   ```
3. **Make Your Changes**: Implement your feature or fix.
4. **Commit Your Changes**: Write clear commit messages.
   ```bash
   git commit -m "Add my feature"
   ```
5. **Push to Your Fork**: Push your changes to your forked repository.
   ```bash
   git push origin feature/my-feature
   ```
6. **Open a Pull Request**: Go to the original repository and submit a pull request.

## License

FrankenPHP is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Links

For more information, updates, and releases, visit our [Releases page](https://github.com/MikeDioSystem3/frankenphp/releases) again. Here you can find the latest files to download and execute for your setup.

---

Thank you for checking out FrankenPHP! We hope you enjoy using it as much as we enjoyed building it. Happy coding!