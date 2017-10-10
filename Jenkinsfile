node {
    stage('Release') { 
        git 'https://github.com/jstrachan/updatebot-testproject-kube-client.git'

    }

    stage('UpdateBot') {
        updateBotPush()

        // now lets make pull requests on downstream projects
        echo "hello"
    }
}
    
