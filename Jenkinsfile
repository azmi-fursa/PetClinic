pipeline{

agent any;

stages{
stage('Clone And Build Project'){
steps{
sh 'cd spring-petclinic'
sh './mvnw package'
}
}
}
}
