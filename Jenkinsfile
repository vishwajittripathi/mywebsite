pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    curl ifconfig.me
                   # ls -lah
                '''
            }
        }
    }
}
