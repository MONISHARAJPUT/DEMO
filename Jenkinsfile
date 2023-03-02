pipeline {
    agent any
        options([disableConcurrentBuilds(), pipelineTriggers([githubPush()])])
            stages {
                stage('MORNING') {
                    steps {
                        echo 'IT IS MORNING'
                    }
                }
                stage('AFTERNOON') {
                    steps {
                        echo 'IT IS AFTERNOON'
                    }
                }
                stage('EVENING') {
                    steps {
                        echo 'IT IS EVENING'
                    }
                }
                stage('NIGHT') {
                    steps {
                        echo 'IT IS NIGHT'
                    }
                }
            }
}
