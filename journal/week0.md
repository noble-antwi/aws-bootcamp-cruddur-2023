# Week 0 — Billing and Architecture
## Required Homeworks done for week 0 
### Installing AWS CLI
This step has been done successfully and can be viewd in the yml file for the week 0 branch created.

The instruction and code can however be viewd below
```
tasks:
  - name: aws-cli
    env:
      AWS_CLI_AUTO_PROMPT: on-partial
       init: |
       cd /workspace
       curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
       unzip awscliv2.zip
       sudo ./aws/installc
       cd $THEIA-WORKSPACE_ROOT


vscode:
  extensions:
    - 42Crunch.vscode-openapi

```
