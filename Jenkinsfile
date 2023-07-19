pipeline {
    agent any
    
    stages {
        stage('Hello from Github') {
            steps {
                echo 'Hello from Github'
            }
        }
    }
    
    triggers {
        pollSCM('* * * * *')
    }
}
