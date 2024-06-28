pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                // Checkout the code from Git
                checkout scm
                // Build with Maven
                sh 'mvn -DskipTests clean package'
            }
        }
    }
}