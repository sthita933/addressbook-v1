pipeline {
    agent any

    stages {
        stage('git checkout') {
            steps {
                git 'https://github.com/sthita933/addressbook-v1.git'
            }
        }
         stage('compilitation the code') {
            steps {
                sh 'mvn compile'
            }
        }
        
    }
}
