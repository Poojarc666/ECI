pipeline {
    agent any 
    stages {
        stage('Static Analysis') {
            steps {
                echo 'Static Analysis' 
            }
        }
        stage('Compile') {
            steps {
                echo 'Compile ' 
            }
        }
        stage('Security Check') {
            steps {
                echo 'Run the security check against the application' 
            }
        }
        stage('Run Unit Tests') {
            steps {
                echo 'Run unit tests from the source code' 
            }
        }
        stage('Run Integration Tests') {
            steps {
                echo 'Run only crucial integration tests from the source code' 
            }
        }
        stage('Publish Artifacts') {
            steps {
                echo 'Save the assemblies generated from the compilation ' 
            }
        }
    }
}
