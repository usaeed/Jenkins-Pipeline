pipeline {
    agent none
    stages {
        stage('Back-end') {
            agent {
                docker { image 'maven:3-alpine' }
            }
            steps {
                sh '#!/usr/bin/sh -xe\n env'
            }
        }
        stage('Front-end') {
            agent {
                docker { image 'node:7-alpine' }
            }
            steps {
                sh '#!/usr/bin/sh -xe\n env'
            }
        }
    }
}
