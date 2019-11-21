#!groovy

node() {
    stage('scm') {
        def co = checkout scm
        echo "checkout info: " + co
    }

    stage('build') {
        currentBuild.result = 'UNSTABLE'
    }
}
