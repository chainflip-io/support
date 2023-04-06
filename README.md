# Chainflip Public Issue Tracking
Public ticketing system for Perseverance issues tracking

Welcome to our Perseverance issue tracking repository! We appreciate your help in identifying and reporting any issues you encounter. To ensure efficient communication and quicker resolution of issues, please follow the guidelines below when submitting an issue.

# Please check the list of existing issues to make sure it hasn't already been identified.

## What to include in your issue

When submitting an issue, please provide the following information:

1. **Title**: A concise and descriptive title that summarizes the issue.

2. **Description**: A clear and detailed description of the issue, including:
   - The steps to reproduce the issue (if applicable).
   - The expected behavior and the actual behavior you observed.
   - A link to your logs, a snippet of them, or log files if you have neither.

3. **Environment**: Specify the environment where you encountered the issue, including:
   - System Specs (Server hardware, endpoint providers, etc.)
   - If you have modified the default setup compared to the docs, and if so, in what way
   - The Version of the node, angine, and runtime you are using

4. **Severity**: Indicate the severity of the issue:
   - **Critical**: The issue is causing crashes, and is preventing the validator/protocol from performing it's functions.
   - **High**: The issue has a significant impact on the performance of the validator/protocol, but the remains functional.
   - **Medium**: The issue is causing minor disruptions to the expected behaviour.
   - **Low**: The issue is an inconvenience or cosmetic issue, not affecting functionality.

5. **Tags/Labels**: Assign relevant tags or labels to help classify and prioritize the issue (e.g., bug, documentation, question).

## Issue Submission Example

Below is an example of how to structure your issue submission:

```
Title: Validator crashes on starting new Epoch

Description:
When an auction concludes, the Chainflip Engine panics and enters a crash loop: here is a link to my logs https://grafana,etc,etc,etc

Environment:

Operating System: Ubuntu20.04
System Specification: Hetzner 4 corde dedicated, 8GB RAM, 1Gbps up/down, Germany, 160GB NVMe disk
Version: chainflip-engine 0.7.3, chainflip-node 0.7.2, runtime version XYZ

Labels: bug

```

We appreciate your contribution! The team and community will review and address the issues as soon as possible. Remember to keep the discussions respectful and on-topic. Together, we can make this project even better!






