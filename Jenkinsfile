pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
                zip helloworld22-${BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md
            }
        }
        
    }
}