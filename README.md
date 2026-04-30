# HTTP Log Analysis Using Splunk SIEM

## Introduction
HTTP (Hypertext Transfer Protocol) log files store information about web server activity such as user requests, responses, status codes, and user agents. This project demonstrates how to upload and analyze HTTP logs using Splunk SIEM to monitor web traffic and detect potential security issues.

---

## Project Objective
- Understand HTTP log structure  
- Upload log data into Splunk  
- Analyze web traffic patterns  
- Detect errors and suspicious activities  

---

## Tools and Technologies
- Splunk SIEM  
- HTTP Log Files (.log / .txt)  
- Web Browser  

---

## Prerequisites
- Splunk installed and running  
- Sample HTTP log files available  
- Basic knowledge of Splunk interface  

---

## Project Workflow

### Step 1: Prepare Log Files
- Collect HTTP log files in `.log` or `.txt` format  
- Ensure logs contain:
  - Timestamp  
  - Request method (GET, POST)  
  - URL  
  - Status code  
  - User agent  

---

### Step 2: Upload Logs to Splunk
1. Open Splunk Web Interface  
2. Go to **Settings → Add Data**  
3. Select **Upload**  
4. Choose your log file  
5. Set source type (e.g., `access_combined`)  
6. Click **Submit**
    

---

### Step 3: Verify Data Upload
