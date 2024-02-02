pipeline {
    agent any
    stages {
        stage('SCM') {
            steps {
                git branch: 'war', url: 'https://github.com/prem744/J09.git'
            }
        }
       stage('BUILD') {
            steps {
                sh 'mvn clean '
                sh 'mvn clean '
            }
        }
    }
}
