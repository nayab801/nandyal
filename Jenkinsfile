pipeline {
    agent none
    
    stages {
        stage('Example') {
            agent any
            options {
                // Timeout counter starts BEFORE agent is allocated
                timeout(time: 10, unit: 'SECONDS')
            }
            steps {
                echo 'Hello World'
            }
        }
    }
}

