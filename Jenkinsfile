pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'mvn -f myapp/pom.xml clean package'
            }
        }
    }
}
