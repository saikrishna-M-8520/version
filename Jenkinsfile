pipeline {
    agent any

    stages {
        stage('Git pull') {
            steps {
                echo 'Git stage of pull'
            }
        }
        stage('Build') {
            steps {
                echo 'Maven build'
            }
        }
        stage('Sonar code quality') {
            steps {
                echo 'Sonar code testing for bugs identification'
            }
        }  
        stage('Artifactory Publish') {
            steps {
                echo 'Nexus artifactory publish'
            }
        }          
    }
}
