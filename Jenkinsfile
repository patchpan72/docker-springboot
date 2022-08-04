pipeline {
    agent { 
        docker { 
            image 'recording2:0.0.1-SNAPSHOT' 
        } 
    }
    stages {
        stage('Build') {
            steps {
                echo 'BUILDING'
            }
        }
        stage('Test') {
            steps {
                echo 'testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploying'
            }
        }
    }
}
