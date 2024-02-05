pipeline {
    agent any // This pipeline will execute on any available agent

    stages {
        stage('Introduction') {
            steps {
                echo 'Welcome to the Jenkins Pipeline demonstration.'
                script {
                    // Sleep for 2 seconds to simulate a pause
                    sleep(2)
                }
                echo 'This is a basic example of a pipeline script.'
            }
        }
        
        stage('Execution') {
            steps {
                echo 'Now, we will execute a simple pipeline step.'
                script {
                    // Sleep for 3 seconds to simulate a longer pause
                    sleep(3)
                }
                echo 'The step has completed execution.'
            }
        }
        
        stage('Conclusion') {
            steps {
                echo 'We are nearing the end of our pipeline.'
                script {
                    // Sleep for 1 second to simulate a short pause
                    sleep(1)
                }
                echo 'Thank you for exploring Jenkins pipelines with us!'
            }
        }
    }
}
