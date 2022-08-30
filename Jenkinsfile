pipeline {
    agent any
    
    tools {nodejs "node"}
    
    stages {
        stage('Build') {
            steps {
                echo 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo "running a test"
                echo './scripts/test.sh'
            }
        }
         stage('Deliver') {
                            steps {
                                echo "chmod +x ./scripts/deliver.sh"
                                echo './scripts/deliver.sh'
                                echo "chmod +x ./scripts/kill.sh"
                                echo './scripts/kill.sh'
                    }
                }
            }
      }