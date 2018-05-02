#!groovy

@Library('nya@git_co')
import se.uhr.nya.build.Git


node() {
    stage('scm') {
        def git = new Git()
        nya = git.checkout_test path: 'repos/nya'

        echo nya.commitId()
        sh "ls -l repos/nya"
    }
}
