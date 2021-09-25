pipeline{

agent any;

stages{
stage('Clone And Build Project'){
steps{
sh 'rm -rf https://github.com/spring-projects/spring-petclinic.git' 
sh 'git clone https://github.com/spring-projects/spring-petclinic.git'
sh 'cd spring-petclinic'
sh './mvnw package'
}
}
}
}
