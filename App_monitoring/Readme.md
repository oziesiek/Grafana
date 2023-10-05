Grafana Monitoring JSON Configuration
Welcome to the Grafana Monitoring JSON Configuration repository! This repository contains a ready-to-use JSON file designed for simple and effective monitoring of your application infrastructure. 
The configuration is organized to monitor servers divided by applications and provides valuable insights into your server's performance metrics, including uptime, CPU and RAM usage over time, and available disk space.

Features
Uptime Monitoring: Keep track of your servers' uptime to ensure uninterrupted service.
CPU and RAM Usage: Monitor CPU and RAM usage patterns to optimize server performance.
Disk Space Usage: Track available disk space to prevent storage issues.

Getting Started
To implement this monitoring scheme in your infrastructure, follow these steps:

Download the JSON Configuration File: Clone or download the JSON configuration file from this repository.
Import into Grafana: Import the configured JSON file into your Grafana instance
Configuration: Open the JSON file and configure the following variables according to your setup:
<br><br>
![image](https://github.com/oziesiek/Grafana/assets/110523018/a747a3f1-aa6d-44b9-b20b-053f34db135d)
<br>
Datasource: Specify the appropriate datasource to connect Grafana with your data source.
Environment: Set the environment (e.g., production, testing) for which you are configuring the monitoring.
Customization: Feel free to modify the configuration to suit your specific requirements. You can customize the setup to monitor different environments such as production, testing, and more.

Before Configuration:<br>
![1](https://github.com/oziesiek/Grafana/assets/110523018/5c1ce8c9-7d74-4a85-b6f0-314ed5495312)
<br>

After Configuration:<br>
![2](https://github.com/oziesiek/Grafana/assets/110523018/a923fe12-889a-4b2e-ac67-29fc862aa3a9)


Note
This configuration is a flexible and scalable solution for monitoring your application infrastructure. Please ensure that you configure the variables (datasource, environment) correctly before deploying the configuration. 
You can modify and extend this setup to accommodate various environments and additional metrics as needed.

Feel free to explore, modify, and enhance this configuration to meet the unique monitoring requirements of your infrastructure. 
If you encounter any issues or have suggestions for improvements, please don't hesitate to open an issue or contribute to the repository.

Happy monitoring! 🚀
