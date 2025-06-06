#  NGINX Log Analyzer

A professional-grade Bash script for comprehensive analysis of NGINX access logs. Extracts and visualizes:
-  Top IP addresses
-  Most requested paths
-  HTTP status code distribution
-  User agent statistics

![Bash](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![NGINX](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)

##  Key Features
**Real-time analysis** - Process live or historical logs  
**Customizable thresholds** - Change result limits via command arguments  
**Report generation** - Saves timestamped analysis reports  
**Error resilient** - Handles missing files and invalid inputs gracefully  
**Lightweight** - No dependencies beyond standard Linux tools  

##  Getting Started

### Prerequisites
- Linux/Unix environment
- NGINX or Apache access logs
- Bash 4.0+ (run `bash --version` to check)

### Installation
```bash
# Download the script
wget https://raw.githubusercontent.com/Nirpesh551/nginx-log-analyzer/main/log-analyzer.sh

# Make executable
chmod +x log-analyzer.sh

# Verify installation
./log-analyzer.sh --help
