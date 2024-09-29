
# **GitHub Issue Summary**

Welcome to the **GitHub Issue Summary** testing project. This project is designed to test the integration between GitHub and email notifications for issue summaries. Please note that this is a testing project and not intended for production use.

## **Table of Contents**

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)
- [License](#license)
- [Contact](#contact)

## **Introduction**

**GitHub Issue Summary** is a test project that demonstrates how to periodically send summaries of GitHub issues via email. This integration helps in staying informed about the project's progress without constantly checking the GitHub platform.

## **Features**

- Fetches summaries of GitHub issues by assignee.
- Counts open and closed issues.
- Sends email notifications with issue summaries.

## **Installation**

To set up the **GitHub Issue Summary** project, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/github-issue-summary.git
   ```
   
2. **Navigate to the Project Directory**
   ```bash
   cd github-issue-summary
   ```

3. **Install Dependencies**
   ```bash
   ballerina build
   ```

4. **Configure the Project**
   - Edit the `Config.toml` file with your GitHub and email credentials.

## **Usage**

To run the project and test the GitHub to email integration:

1. **Run the Project**
   ```bash
   ballerina run github-issue-summary
   ```

2. **Verify Email Notifications**
   - Check the recipient email inbox for the issue summary notifications.

## **Acknowledgments**

The source code is developed and maintained by [WSO2](https://wso2.com/) . We acknowledge and appreciate the contributions of everyone involved in its development.

- **Original Authors:** [WSO2 Development Team](https://wso2.com/)
- **Special Thanks:** The [Ballerina community](https://ballerina.io/) for providing the integration tools and documentation.

## **License**

Copyright © 2024 Ballerina. All rights reserved.

**GitHub Issue Summary** is licensed under the MIT. For more details, please refer to the LICENSE file included in this repository.

## **Contact**

For any questions or inquiries regarding this testing project, please contact us at [contact email or URL].

Thank you for testing **GitHub Issue Summary**!

Repo ID - ES87347345
