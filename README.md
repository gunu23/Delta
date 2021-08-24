# Delta
## Login to Github and create a new public repo with readme.md
## go to gihub repo settings> select branches > add rule > master (apply rules to master branch)
- check {required pull request reviews before merging}; change the no. of code reviewers as you like> 
- check {require review from code owners} > 
- check:{ Required status checks to pass before merging } > 
- include administrators > 
- create
## setup Trello OR khanban board, ZenHub
## ZenHub > workspace name {Deltaworkspace} > description > next > 
- create few new issues
- issues > new issues > learn git/github > write (description} > assignees > submit new issue. 
// https://www.linkedlin.com/learning/git-essential-training-the-basics
//https://learning.oreilly.com/videos/learn-git-in/9781789348231
## open watson knowledge studio https://www.ibm.com/cloud/watson-knowledge-studio
- create Workspace {Delta} {Identify custom entities and relations in your data. Learn more create entitites and relations workspace}
- click on current workspace (Delta) 
** To create a model:
***rule based model and ML model
- Entity types> Rule-based Model > rules > ok > dictionary > {list of words} > save
-versions > save for deployments
There are two routs {NLU/Watson Discovery)
reg. experssion, dictionaries, rules

- Entity Types > machine learning model > annotation > 

##open terminal > go to doc folder> clone git repo that you created earlier
##setup a new VM
-conda
-apmg
##using anaconda
- conda create --name DeltaEnv python=3.7 
- proceed > y
### To activate env type >
$ conda activate DeltaEnv

to exit: conda: deactivate

##open IDE that you want to work with (pycharm)
- new proj
-doc > delta repo >
###set up UI
webversion of API : Timatic {check rules for your destination and fill out info
when searching you can use CMD + OPT + i to open devloper console
-click network
- click check on search field to see what's on GET req. 
--GET > Response > access token displays
--Post > Response >
-- right click to POST req > copy > copy as cURL > 
***https://curl.trillworks.com and paste curl command to python request
This is a way to get arond witout having an API access to front end UI

Build a new file:
file > new > new new python file > get_requirements.py
file > new> new new python file > test.py

Copy python requests code > paste inside get_requirements.py file

Example:
import requests
def get_requirements():
  sdlkfsdf
  ksdfhsdf
return response.json()
print (get_requirements())

Go back to terminal and run
$pyhon get_requirements.py
$conda instal requests
proceed (Y/N)? y













