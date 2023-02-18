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

### Setting up logical structure of the crudder app using Lucid Chart.
I drew the logical structure of the app using lucid chart as disp;ayed below:
![Logical Layout](https://github.com/noble-antwi/aws-bootcamp-cruddur-2023/blob/main/journal/assets/cruddder%20logical%20diagram.PNG)


[The link to the diagram on lucid chart website](https://lucid.app/lucidchart/e946d2ee-8160-41bc-9305-015b791dd937/edit?view_items=Tmjy1IP2h9UG&invitationId=inv_89ef2ada-a46e-41eb-a73c-efbf7e56b892)


### Creating a Billing Alarm in AWS
I also created a budget alarm which got triggered later in the week.
The images below will show the budget creation confirmation as well as the alert when the alarm was triggered.
![Budget Creation]()