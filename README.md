# cptd-plugin-gateway
A new command named gateway has been added to the CPTD CLI system.  
This command is designed to analyze the network configuration of Linux systems and allows you to:  

Display the current default gateway and additional routes  
Show a list of open ports (TCP and UDP)  
Filter the output: gateways only, ports only, TCP only, or UDP only  
Save the result to a file if needed  
The command works exclusively on Linux. It automatically checks the operating system compatibility on startup.  

Usage Examples:  
cptd gateway  
cptd gateway --only-gateway  
cptd gateway --only-ports --tcp 
cptd gateway --all --save report.txt  
Installation:  
cptd command --add gateway.zip  
Command Information:  

Name: gateway  
Version: 1.0  
Author: Asbjorn Rasen  
Dependency: colorama  
License: CPTD-DSL License v1.1  
Repository: https://github.com/asbjornrasen  
