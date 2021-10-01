// properties([pipelineTriggers([githubPush()])])

pipeline {
//     triggers {
//         pollSCM('') //Empty quotes tells it to build on a push
//     }
    agent any
    
    stages {
        stage ('Checkout'){
            steps {
                git branch: 'main', url: 'https://github.com/cahyaramadhan/jenkinsRepo1.git'
            }
        }
        stage ('Build'){
            steps {
              bat "echo Building..."
            }
        }
        stage ('Test'){
            steps {
              bat "echo Testing..."
            }
        }
    }
}    
