node {
    stage('Build') {
        // Custom build steps
        sh 'npm install'
        sh 'npm build'
    }

    stage('Test') {
        // Custom test steps
        sh 'npm test'
    }

    stage('Deploy') {
        // Custom deployment steps
        sh 'kubectl apply -f deployment.yaml'
    }
}
