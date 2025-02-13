@Library('shared-library') _

pipeline {
    agent any
    stages {
        stage('hello') {
            steps {
                hello('World')  // Calls the global variable function
                script {
                    echo " $string" // Calls the custom class method
                }
            }
        }
    }
}
