pipeline{

agent slave;

stages{
stage('Clone And Build Project'){
steps{
git clone 'https://github.com/spring-projects/spring-petclinic.git'
cd spring-petclinic
sh ./mvnw package
}
}
}
}
