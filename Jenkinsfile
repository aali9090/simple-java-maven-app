pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                // Checkout the code from Git
                checkout scm
                // Build with Maven
                bat 'mvn -B -DskipTests clean package'
            }
        }
    }
}