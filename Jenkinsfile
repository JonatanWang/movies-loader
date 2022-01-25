node ('workers') {
    stage('Checkout') {
        steps {
            git branch: 'develop',
                credentialsId: 'github-ssh',
                url: 'git@github.com:JonatanWang/movies-loader.git'
        }
    }
}