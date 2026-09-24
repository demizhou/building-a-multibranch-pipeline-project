pipeline {
    agent any /*{
        docker{
            image 'node:6-alpine'
            args '-p 3000:3000 -p 5000:5000' 
        }
    }*/
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
				echo "=== Build stage ==="
                //sh 'npm install'
            }
        }
        stage('Test') {
            steps {
				echo "=== Test stage ==="
                //sh './jenkins/scripts/test.sh'
            }
        }
    }
}
