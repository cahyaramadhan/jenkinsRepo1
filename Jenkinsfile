// properties([pipelineTriggers([githubPush()])])

pipeline {
    triggers {
        pollSCM('') //Empty quotes tells it to build on a push
    }
    stage ('Checkout'){
        git branch: 'main', url: 'https://github.com/cahyaramadhan/jenkinsRepo1.git'
    }
    stage ('Build'){
      bat "echo Building..."
    }
    stage ('Test'){
      bat "echo Testing..."
    }
}    
