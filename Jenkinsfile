pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh '#!/usr/bin/sh -xe\n env'
            }
        }
    }
}
