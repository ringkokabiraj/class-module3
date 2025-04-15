pipeline {
    agent {
        label 'production-server'
    }
    
    stages {
        stage('Production Server service') {
            steps {
                script {
                    git branch: 'main', url: 'https://github.com/ringkokabiraj/class-module3.git'
		    sh 'npm install'
                    echo "Congratulations"
                }
            }
        }
    }
}
