pipeline {
    agent any
    stages {
        stage ("build"){
            steps {
                script {
                    sh 'chmod +x gradlew'
                    sh './gradlew build'
                }
            }
        }
    }
}