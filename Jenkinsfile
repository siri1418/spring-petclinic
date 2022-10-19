pipeline{
    agent{label 'jenkins'}
    stages{
        stage('clone it'){
            steps{
                git url:'https://github.com/saisatyateja/spring-petclinic.git',
                branch:'main'
            }
        }
        stage('build it'){
            steps{
                sh 'mvn package'
            }
        }  
    }
}