Gophish Remastered: Enhanced Open-Source Phishing Toolkit

Gophish Logo
Build Status GoDoc

Gophish Remastered brings an upgraded, open-source phishing framework tailored for advanced security professionals, penetration testers, and organizations. With a streamlined setup and enhanced functionality, Gophish Remastered enables efficient phishing simulations and comprehensive security awareness training.
Key Features

    Cross-Platform Availability: Compatible with Windows, macOS, and Linux.
    Fast Deployment: Minimal configuration for launching phishing campaigns.
    Enhanced Security Training: Ideal for real-world simulations and improving phishing resilience.

Installation

Installing Gophish Remastered is simple. Download and extract the appropriate release package for your system, then run the binary to begin.
Building from Source

To build Gophish Remastered from source, ensure Go v1.10 or newer is installed. Clone the repository and compile with the following commands:

bash

git clone https://github.com/gophish/gophish.git
cd gophish
go build

A gophish binary will be created in the project directory.
Docker Support

Gophish Remastered is also available as an official Docker image. Get started by pulling the image from Docker Hub:

bash

docker pull gophish/gophish

For additional information, visit the Docker Hub page.
Setup

After starting the Gophish Remastered binary, access the dashboard by visiting https://localhost:3333 in a web browser. The log output will provide default login credentials, such as:

plaintext

time="2020-07-29T01:24:08Z" level=info msg="Please login with the username admin and the password 4304d5255378177d"

For versions prior to v0.10.1, the default credentials are:

    Username: admin
    Password: gophish

Documentation

Extensive documentation is available on the Gophish website. For suggestions or to address missing documentation, feel free to submit an issue to enhance our resources.
Reporting Issues

Encounter any bugs, feature requests, or missing information? File an issue to help us improve. We value community feedback to continually enhance Gophish Remastered.
License

Gophish Remastered is licensed under the MIT License:

vbnet

The MIT License (MIT)
Gophish - Open-Source Phishing Framework

© 2013 - 2020 Jordan Wright

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files, to deal in the Software
without restriction, including without limitation the rights to use, copy,
modify, merge, publish, distribute, sublicense, and/or sell copies of the Software,
and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

This software is provided "AS IS", without warranty of any kind.

Visit Gophish's official site for more information.
