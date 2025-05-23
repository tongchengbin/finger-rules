# Finger-Rules | Fingerprint Rule Library

<p align="center">
  <img src="https://img.shields.io/github/license/tongchengbin/finger-rules" alt="License">
  <img src="https://img.shields.io/github/stars/tongchengbin/finger-rules?style=social" alt="Stars">
  <img src="https://img.shields.io/github/forks/tongchengbin/finger-rules?style=social" alt="Forks">
</p>

[English](README.md) | [中文](README_CN.md)

## Introduction

Finger-Rules is a comprehensive open-source fingerprint rule library for web application identification. It contains detection rules for various web technologies, including web servers, content management systems, frameworks, WAFs, network devices, and more.

This rule repository is designed to work with [AppFinger](https://github.com/tongchengbin/appfinger), a multi-protocol fingerprint matching tool that helps security researchers and penetration testers identify technologies used by web applications.

## Features

- **Extensive Coverage**: Contains rules for thousands of web technologies and applications
- **Multi-protocol Support**: Includes HTTP, FTP, SSH, and more protocols
- **Regularly Updated**: Continuously maintained with new fingerprints
- **Easy to Use**: Simple YAML format for easy contribution and integration
- **High Accuracy**: Precise matching patterns to minimize false positives

## Rule Categories

- Web Application Firewalls (WAF)
- Content Management Systems (CMS)
- Web Frameworks
- Web Servers
- Network Devices (Routers, Switches, etc.)
- IoT Devices
- Cloud Services
- And more...

## Usage

These rules are designed to be used with [AppFinger](https://github.com/tongchengbin/appfinger). To use them:

1. Clone this repository
2. Use AppFinger with the `-d` flag to specify the rules directory:

```bash
appfinger -u https://example.com -d /path/to/finger-rules
```

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch for your feature
3. Add or modify rules following the existing format
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
