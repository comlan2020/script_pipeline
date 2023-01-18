 pipeline {
    agent any

    stages {
        stage('create a zip file') {
            steps {
            sh 'zip Script_pipeline-${BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md '  

            }
    
            }
        }
    }
