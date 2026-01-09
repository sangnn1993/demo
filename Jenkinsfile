pipeline {
    agent any  // Chạy trên bất kỳ agent nào có sẵn
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World từ Jenkins Pipeline!'
            }
        }
        stage('list file') {
            steps {
                sh "ls -la"
            }
        }
    }
}