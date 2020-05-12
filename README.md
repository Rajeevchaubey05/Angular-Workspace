## Command to create Angular workspace
P:\ProgrammingSpace\AngularProjects\Angular-Workspace>ng new ngworkspace --createApplication="false"
P:\ProgrammingSpace\AngularProjects\Angular-Workspace>cd ngworkspace

## Command to create Angular applications

## Creation command of 1st application(application-first): 
P:\ProgrammingSpace\AngularProjects\Angular-Workspace\ngworkspace>ng g application application-first

## Creation command of 2nd application(application-second): 
P:\ProgrammingSpace\AngularProjects\Angular-Workspace\ngworkspace>ng g application application-second

## After running above command, 2 folders will be created under projects:

P:\ProgrammingSpace\AngularProjects\Angular-Workspace\ngworkspace\projects

1. application-first
2. application-second

## Change the below configuration as per need of application

File name: angular.json
"defaultProject": "application-first"

## For example, if you need to run application-second,change above configuration as below
"defaultProject": "application-second"

## To see the difference, run below command after eaach modification
ng serve
