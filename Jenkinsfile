pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        stage('test') {
            steps {
                 echo "Hello ravali"
            }
        stage('test2') {
            steps {
                 echo "Hello ravali, Iam testing"
            }
        }
    }
}
    }
}
