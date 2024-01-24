# Title : Webmin XSS
# Researcher : Red-Shield Security Lab
# Product : Webmin
# Version Affected : 2.105 and below
# CVE-ID:CVE-2023-52046
# Description: There is a stored cross-site scripting (XSS) vulnerability in Webmin 2.105 and below via the "Execute cron job as" tab Input field, which allows attackers to run malicious scripts by injecting a specially crafted payload.
# Vulnerability Type:XSS
# Date : 23th Dec 2023
# Step 1 : Go to admin login
# Step 2 : Navigate to webmin tab.
# Step 3 : Go to System.
# Step 4 : Go to Scheduled Cron Jobs.
# Step 5 : Create a new scheduled cron job.
# Step 6 : wirte the payload( "><img src=# onerror=prompt(1)> ) in Execute cron job as 
# Step 7 : then click creat 

XSS will execute. 
