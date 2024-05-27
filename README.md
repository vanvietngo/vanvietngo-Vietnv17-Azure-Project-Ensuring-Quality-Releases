# Project Starter
This repository contains the starter code for the **Ensuring Quality Releases** project of the cd1807 Ensuring Quality Releases (Quality Assurance) course taught by Nathan Anderson. 


## How to use?
- Fork this repository to your Github account and clone it locally for further development. 
- Follow the classroom instructions, and check the rubric before a submission. 

## Suggestions and Corrections
Feel free to submit PRs to this repo should you have any proposed changes. 

<!--  -->

mkdir azagent;cd azagent;curl -fkSL -o vstsagent.tar.gz https://vstsagentpackage.azureedge.net/agent/3.239.1/vsts-agent-linux-x64-3.239.1.tar.gz;tar -zxvf vstsagent.tar.gz; if [ -x "$(command -v systemctl)" ]; then ./config.sh --environment --environmentname "myenv-vm" --acceptteeeula --agent $HOSTNAME --url https://dev.azure.com/odluser259749/ --work _work --projectname 'AZUREDEVOPS-FINAL' --auth PAT --token ykugtnxyp5zdl4vhgdubav3otrwi3octveuu5qn7ivc4tyeqtgyq --runasservice; sudo ./svc.sh install; sudo ./svc.sh start; else ./config.sh --environment --environmentname "myenv-vm" --acceptteeeula --agent $HOSTNAME --url https://dev.azure.com/odluser259749/ --work _work --projectname 'AZUREDEVOPS-FINAL' --auth PAT --token ykugtnxyp5zdl4vhgdubav3otrwi3octveuu5qn7ivc4tyeqtgyq; ./run.sh; fi

<!--  -->