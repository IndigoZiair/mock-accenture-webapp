pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Command to build the project using Gradle
                sh './gradlew assemble'
            }
        }

        stage('Test') {
            steps {
                // Command to run tests using Gradle
                sh './gradlew test'
            }
        }

        // Add additional stages as needed
    }
}

