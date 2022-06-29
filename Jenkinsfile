pipeline {
    agent { 
        docker { 
            image 'recording2:0.0.1-SNAPSHOT' 
        } 
    }
    stages {
        stage('build') {
            steps {
                echo 'BUILDING'
            }
        }
        stage('test') {
            steps {
                echo 'testing'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying'
            }
        }
    }
}
