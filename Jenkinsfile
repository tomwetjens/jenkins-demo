pipeline {
    agent any
    triggers {
        cron('H 5/* 0 0 0')
    }
    stages {
        stage('Build and Test') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Publish') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Deploy to DEV') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Component Tests') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Deploy to TEST') {
            steps {
                echo 'Hello World'
            }
        }
        stage('System Tests') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Deploy to ACC') {
            when { branch 'master' }

            input 'Deploy to ACC?'

            steps {
                echo 'Hello World'
            }
        }
        stage('Acceptance Tests') {
            when { branch 'master' }

            steps {
                echo 'Hello World'
            }
        }
        stage('Deploy to PROD') {
            when { branch 'master' }

            input 'Deploy to PROD?'

            steps {
                echo 'Hello World'
            }
        }
    }
}