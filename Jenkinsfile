node {
    docker.image('node:16-buster-slim').withRun('-p 3000:3000') {
        sh 'echo "prepare node"'
    }

    stage('Build') {
        sh 'npm install'
    }
}