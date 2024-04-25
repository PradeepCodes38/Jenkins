pipeline {
  // Define the start of the Jenkins Declarative Pipeline
  agent {
    // Specify where the pipeline will execute
    docker { image 'node:16-alpine' }
    // Use a Docker container with the Node.js 16 Alpine image
  }
  stages {
    // Define stages for the pipeline
    stage('Test') {
      // Define a stage named "Test"
      steps {
        // Specify the actions to be executed in this stage
        sh 'node --version'
        // Execute the shell command 'node --version' inside the Docker container
      }
    }
  }
}

