pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                echo "Welcome"
                sh 'git log'
            }
        }
        stage('Test'){
            steps {
                echo "Test"
            }
        }
        stage('Deploy') {
            steps {
                sh 'pwd'
            }
        }
    }
}
