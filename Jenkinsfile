pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo "PATH = ${PATH}"
		echo "M2_HOME = ${M2_HOME}"
		sh 'mvn -f path/to/D:/Good/Good/myapp/pom.xml clean package'
            }
        }
    }
}
