node {
    docker.image('node:16-buster-slim').inside('-p 3000:3000') {
        stage('Build') {
            sh 'node --version'
            sh 'npm install'
        }
    }
}