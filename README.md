# Scripting

## What is scripting?

Scripting in Python refers to a plain text that contains Python code that is intended to be directly executed by the user. It is one of the most practised Python program.
Scripting is used for automation of daily tasks, reporting server management, security, automating software and many more.
## Why is scripting important for Devops engineers?
Scripting is vital for DevOps engineers because automation is very important for the DevOps process as it aims to reduce the time it takes to perform the manual programming. Scripting allows DevOps enegineers to automate the tasks which can be repeatable across multiple environment and applications iterations. This means that if an automated tasks needs to be performed multiple times so creating a script helps to use in each environment. Scripting also makes it clear as it provides instructions on how to perform task which can help in reducing the errors. 
 - Automation
 - Configuration/consistency
 - Efficient
## Here are just some examples of way we use scripts in DevOps:

- Python script to query a database
- Python script to execute a shell command or script
- Query logs for alerts
- Python script to take a backup
- Python script for K8 containers
- Python script to fetch I.P's of an autoscaling group
- Lambda function to stop instances on a weekend
- Python script for ETL jobs
- Find the expiry date of an SSL certificate
- Develop CLI applications using Python
- Automating CRUD
- Custom scripts for config management
# Scripting vs Programming
## Scripting
- Simple
- Easy to read
## Programming
- Difficult
- Hard to read

# Why Phyton for DevOps?
- Easy
- Libraries
- Language Interoperability 
- Large Community-- open source

## Basics of Scripting in Python.
Libraries and Modules- Module is a collection of function and a library is much bigger collection of modules. 
Libraries- Bigger and Modules- Smaller.

## There are Seven "core" modules in Python.
- sys (system) -> print(sys.version) #  Gives you python version
- os (operator system) -> print(os.getcwd()) # gets current working directory
- subprocess ->subprocess.run(["python", "hello_world.py"]) # It runs an external file when executed 
- math -> 
- random -> prints random number
- datetime -> prints the current date and time
- json -> 

## Important Python Modules for DevOps
- os (Interacting with the operating system)
- platform (Access to underlying platform data)
- subprocess (Subprocess management)
- sys (System specific parameters and functions)
- psutil (Process and system utilities)
- re (Regular Expression Operations)
- scapy (Packet manipulation)
- Requests (HTTP library)
- urllib3 (HTTP client)
- logging (Error logging)
- getpass (Portable password input)
- boto3 (AWK Software development kit, SDK. Allows interaction with AWS from Python)
- paramiko (SSH)
- JSON (JSON encoder and decoder
- PyYAML (YAML parser & emitter for Python)
- pandas (Data science, but useful for automating CSV's)
- smtplib (STMP)

## Using os to do things
import os
import subprocess

stores the file path to the current file
script_dir = os.path.dirname(__file__)
stores the filepath to the script you want to run
script_absolute_path = os.path.join(script_dir + "/script.sh")
calls the shell file and runs it
subprocess.call(['sh', script_absolute_path])

