pipeline {
    agent any
    /** triggers { pollSCM '* * * * *' } **/
    /** properties([pipelineTriggers([[$class: 'GitHubPushTrigger'], pollSCM('* * * * *')])]) **/
    /** triggers {
      githubPush()
    } **/
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
