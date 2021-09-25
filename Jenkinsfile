pipeline{

agent slave

stages{
stage('Clone And Build Project'){
steps{
sh 'git clone https://github.com/spring-projects/spring-petclinic.git'
sh 'cd spring-petclinic'
sh './mvnw package'
}
}
}
}
