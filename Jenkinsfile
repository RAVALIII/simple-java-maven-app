pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        stage('tetsing') { 
            steps {
                ech 'ravali In testing' 
            }   
        }
        }
    }
}
