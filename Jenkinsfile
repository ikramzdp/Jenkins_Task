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
        // Poll SCM trigger to check for changes on the GitHub repository
        pollSCM('* * * * * *') // Poll every minute
    }
}
