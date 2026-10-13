pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git branch: 'master',
                url: 'https://github.com/varunlaxman3321/steve-sundar.git'
            }
        }
        
        stage('build') {
            steps {
                echo 'build started'
                sh 'ls -la'
            }
        }
        
        stage('test') {
            steps {
                echo 'test completed'
            }
        }
        
        stage('deploy') {
            steps {
                echo 'deployment finished'
            }
        }
    }
}
