node(POD_LABEL) {
    stage('Get a Maven project') {
        git 'https://github.com/jenkinsci/kubernetes-plugin.git'
        container('maven') {
            stage('Build a Maven project') {
                sh 'mvn -B clean install'
            }
        }
    }
}
