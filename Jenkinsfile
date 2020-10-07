pipeline {
    agent { 
        label 'master'
        }
    stages {
        stage('Build') {
            steps {
                echo "Building ... "
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploing ..."
            }
        }
        stage('Sweep') {
            steps {
                echo "Sweeping ..."
            }
        }
    }
}
