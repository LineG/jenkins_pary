def gv

pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                script {
                    echo "building the app ..."
                }
            }
        }
        stage("test") {
            steps {
                script {
                    echo "testing the app ..."
                }
            }
        }
        stage("deploy") {
            steps {
                script {
                    echo "deploying the app ..."
                }
            }
        }
    }   
}