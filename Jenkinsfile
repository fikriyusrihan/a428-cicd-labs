node {
    properties([
        pipelineTriggers([
            [$class: 'SCMTrigger', scmpollspec: '*/2 * * * *']
        ])
    ])

    docker.image('node:16-buster-slim').withRun('-p 3000:3000')

    stage('Build') {
        sh 'npm install'
    }
}