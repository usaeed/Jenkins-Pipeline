pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh """\
                #!/bin/sh
                echo hello sh!
            }
        }
    }
}
