#!groovy

@Library('nya')
import se.uhr.nya.build.Git


node() {
    stage('scm') {
   def checkoutInfo = checkout changelog: true,
            scm: [$class           : 'GitSCM',
                  extensions       : [
                          [$class: 'CleanBeforeCheckout'],
                          [$class: 'hudson.plugins.git.extensions.impl.RelativeTargetDirectory', relativeTargetDir: "repos/nya"],
                  ]]


        echo "----" + checkoutInfo

        sh "ls -l repos/nya"
    }
}
