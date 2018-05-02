#!groovy

@Library('nya')
import se.uhr.nya.build.Git


node() {
    stage('scm') {
        def checkoutInfo = checkout scm

        echo "----" + checkoutInfo

        sh "ls -l repos/nya"
    }
}
