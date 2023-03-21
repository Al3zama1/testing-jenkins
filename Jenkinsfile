Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { 
        node {
            label 'learn'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                echo 'what is this'
            }
        }
    }
}
