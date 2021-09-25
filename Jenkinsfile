pipeline{

agent any;

stages{
stage('Clone And Build Project'){
steps{
rm -rf *
sh 'git clone https://github.com/spring-projects/spring-petclinic.git'
sh 'cd spring-petclinic'
sh './mvnw package'
}
}
}
}
