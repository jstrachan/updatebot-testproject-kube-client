node {
    stage('Release') { 
        git 'https://github.com/jstrachan/updatebot-testproject-kube-client.git'

    }
    updateBotPush()

    stage('UpdateBot') {
        // now lets make pull requests on downstream projects
        echo "hello"
    }
}
    
