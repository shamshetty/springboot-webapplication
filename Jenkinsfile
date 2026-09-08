pipeline{
    agent any
    stages{
        stage("Checkout"){
            steps{
                git branch: 'master',
                    url: 'https://github.com/shamshetty/springboot-webapplication.git'
            }
        }
        stage("Build_Artifact"){
            steps{
                sh "mvn clean package"
            }
        }
    }
}
