properties([pipelineTriggers([githubPush()])])

node {
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
