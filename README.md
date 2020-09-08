# microservice-project
This is the main repository for the microservice project
Clone the repository and its submodules using:
git clone --recurse-submodules https://github.com/samhamra/microservice-project.git

Optional fix for detached head:

git submodule update 
git submodule foreach git checkout master 
git submodule foreach git pull origin master 
