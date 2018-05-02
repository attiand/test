#!groovy

@Library('nya')
import se.uhr.nya.build.Git


node() {
    stage('scm') {
        def co = checkout scm


        echo "----" + co
    }
}
