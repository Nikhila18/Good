pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo "PATH = ${PATH}"
		echo "M2_HOME = ${M2_HOME}"
		sh 'mvn clean package'
            }
        }
    }
}
