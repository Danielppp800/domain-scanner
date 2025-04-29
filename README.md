# Domain Scanner 🌐

![Domain Scanner](https://img.shields.io/badge/Domain%20Scanner-v1.0.0-blue)

Welcome to **Domain Scanner**, a powerful and flexible tool for checking domain name availability, written in Go. This tool helps you find available domain names based on various patterns and filters. 

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Flexible Patterns**: Check domain names based on custom patterns.
- **Multiple TLD Support**: Search across various top-level domains (TLDs).
- **Fast and Efficient**: Built with Go for optimal performance.
- **Simple Interface**: User-friendly command-line interface for easy use.
- **Open Source**: Free to use and modify.

## Installation

To get started with Domain Scanner, download the latest release from the [Releases](https://github.com/Danielppp800/domain-scanner/releases) section. After downloading, execute the binary for your platform.

### Step-by-Step Installation

1. Visit the [Releases](https://github.com/Danielppp800/domain-scanner/releases) page.
2. Download the appropriate binary for your operating system.
3. Unzip the downloaded file.
4. Move the binary to a directory in your PATH for easy access.

## Usage

Once installed, you can use Domain Scanner directly from your command line. The basic syntax is:

```bash
domain-scanner [options] <pattern>
```

### Options

- `-t, --tld <tld>`: Specify the TLD to check (e.g., .com, .net).
- `-f, --filter <filter>`: Apply filters to your search.
- `-h, --help`: Display help information.

### Example Commands

1. Check availability for a specific pattern:

```bash
domain-scanner example.com
```

2. Search for multiple TLDs:

```bash
domain-scanner -t com,net example
```

3. Apply a filter to your search:

```bash
domain-scanner -f available example
```

## Examples

Here are some practical examples to help you get started:

### Example 1: Basic Availability Check

To check if `example.com` is available, simply run:

```bash
domain-scanner example.com
```

### Example 2: Multiple TLDs

If you want to check the availability of `example` across `.com`, `.net`, and `.org`, use:

```bash
domain-scanner -t com,net,org example
```

### Example 3: Using Filters

To find available domains with a specific pattern, use:

```bash
domain-scanner -f available mysite
```

## Contributing

We welcome contributions to Domain Scanner! If you have suggestions or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your fork.
5. Open a pull request with a description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out:

- **GitHub**: [Danielppp800](https://github.com/Danielppp800)
- **Email**: daniel@example.com

Thank you for using Domain Scanner! We hope it helps you find the perfect domain name. Don't forget to check the [Releases](https://github.com/Danielppp800/domain-scanner/releases) for the latest updates and features.