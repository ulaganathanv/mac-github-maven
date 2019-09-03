# Repository for Reference - Github and Maven Commands

## Git Commands

git config --global http.sslVerify "false"

git config --list - To list all the configuration values.  
git config --list --global - To list all the global configuration values.  

git config user.email "ulag.india@gmail.com" - To update the email.  

git config --global user.name "Ulaganathan Vallinayagam" - To update the global user name. 
git config --global user.email "ulag.india@gmail.com" - To update the global email. 

git branch -b <branch_name> - To create a new branch.  
git clone -b "development" https://code.company.com/metricsapp/metrics-app.git  
git clone --branch release/Phase3_Day3 https://<username>@g<location>project.git - To clone from a specific branch.  
git checkout <branch_name> - To switch over to other branch.  

git reset --hard - To revert all your local changes.

git stash - To move your local changes to Hash.
git stash pop - To bring back the changes to local from Hash.

git merge <branch_name> - Go to the source branch and use this command to pull the latest contents from the destination branch.

git pull origin <branch_name> - To pull the contents from other branch to local.
git push origin <branch_name> - To push the contents to other branch to local.

## Maven Commands

mvn clean install -DskipTests - To skip the test case execution.  
mvn spring-boot:run - To start the application from local command prompt.  
mvn clean install -P dev - To run the testcases with dev profile.  
