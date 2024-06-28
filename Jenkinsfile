pipeline{
    agent any
    stages{
        stage('Checkout') {
            steps {
                // Checkout the code from Git
                git 'https://github.com/aali9090/simple-java-maven-app.git'
            }
        }
        stage('Build') {
            steps {
                // Build and test with Maven
                bat 'mvn clean package'
            }
        }
    }
}