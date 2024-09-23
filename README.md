# Table of Contents

1. [Features](#Features)
2. [Pre-Requisites](#Pre-Requisites)
3. [Installation and Running the code](#Installation-and-Running-the-code)
4. [Usage Example](#Usage-Example)
5. [YAML Configuration](#Sample-YAML-Configuration)
6. [Explaination of Availability Calculation](#Explanation-of-Availability-Calculation)
7. [Troubleshooting](#Troubleshooting)
8. [Future Scope](#Future-Scope)
9. [Contributing](#Contributing)
10. [License](#License)


# Features

1. Reads endpoints from a YAML configuration file.

# Pre-Requisites

1. Python 3.7+: This project is written in Python and requires Python version 3.7 or later.

# Installation and Running the code

1. Clone the repository to your local machine, run the following commands one by one in the terminal:

# Usage Example

  method: GET
# Sample YAML Configuration

The YAML configuration file defines the endpoints that the program will monitor. Here’s an example 
# Explanation of Availability Calculation

The program considers an endpoint UP if:

# Troubleshooting

- Missing Dependencies: If you get an error like ModuleNotFoundError: No module named 'requests' or No module named 

# Future Scope

In the future, to enhance monitoring and alerting for this health checker, we can integrate with AWS CloudWatch for real-time observability and automated alerts.


# Contributing

Feel free to fork this repository and make pull requests. Contributions to improve the codebase and add new features are welcome. Please ensure that your contributions adhere to Python best practices.

# License

This project is licensed under the MIT License. See the LICENSE file for more details
