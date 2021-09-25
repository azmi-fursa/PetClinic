pipeline{

agent any;

stages{
stage('Clone And Build Project'){
steps{


git branch: 'main', url: 'https://github.com/spring-projects/spring-petclinic'
sh 'cd spring-petclinic'
script{
	"./mvnw package"
}
}
}
}
}

