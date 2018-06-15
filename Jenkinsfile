pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                bat returnStdout: true, script: 'mvn -B -DskipTests clean package'
            }
        }
    }
}
