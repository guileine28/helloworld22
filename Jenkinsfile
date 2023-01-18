pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
              sh  'zip helloworld22-${BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md'
            }
        }
        
    }
}