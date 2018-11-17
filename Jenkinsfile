pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
        stage('Stage 2'){
            steps{
                input('Do you want to proceed?')
            }
        }
    }
}
