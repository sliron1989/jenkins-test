podTemplate {
node(POD_LABEL) {
    stage('Test') {
            try {
                sh 'mkdir test'
                println "dir test created successfuly"
            }
            catch(err) {
                println "dir test doesnt exist"
            }
        }
    }
}
