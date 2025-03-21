pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                echo 'git checkout..'
            }
        }
        stage('Compile') {
            steps {
                echo 'Compile..'
            }
        }
        stage('Test') {
            steps {
                echo 'Test..'
            }
        }
        stage('SonarQube Analysis') {
            steps {
                echo 'SonarQube Analysis..'
            }
        }
        stage('Quality Gate Check') {
            steps {
                echo 'Quality Gate Check..'
            }
        }
        stage('OWASP Dependency Check') {
            steps {
                echo 'OWASP Dependency Check..'
            }
        }
        stage('Trivy FileScan') {
            steps {
                echo 'Trivy fs..'
            }
        }
        stage('build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Artifact Push') {
            steps {
                echo 'Artifact Push..'
            }
        }
        stage('Docker Image & Tag') {
            steps {
                echo 'Image Build..'
            }
        }
        stage('Trivy Image Scan') {
            steps {
                echo 'Trivy image..'
            }
        }
        stage('Docker Push Image') {
            steps {
                echo 'Push Docker Image..'
            }
        }  
    }
}
