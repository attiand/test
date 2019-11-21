#!groovy

node() {
    stage('scm') {
        def co = checkout changelog: true, scm
        echo "checkout info: " + co       
    }
}
