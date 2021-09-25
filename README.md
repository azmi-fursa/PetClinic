# First HomeWork
in our first homework by nader, we were asked to create a jenkins job that does the following:

clones a project called PetClinic, we do so by:

entering the pipeline syntax, choosing the git:Git option, entering the url of our repository in git, choosing the main b

ranch (or whatever branch the repository is on), and pressing the generate pipeline script to get the git branch command.

after cloning the project, next we will build the project by entering the command cd spring-petclinic which will change the directory to spring-petclinic, next we will build the project using ./mvnw package.

we run the application on the jenkins slave by entering the agent {label 'slave'} command, and to confirm that its working we go into jenkins and press build now.

