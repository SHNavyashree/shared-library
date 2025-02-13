@Library('shared-library') _

pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                example('World')  // Calls the global variable function
                script {
                    com.example.MyClass.greet('World')  // Calls the custom class method
                }
            }
        }
    }
}
