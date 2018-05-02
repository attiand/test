#!groovy

@Library('nya')
import se.uhr.nya.build.Git


node() {
    stage('scm') {
        def git = new Git()
        nya = git.checkout path: 'repos/nya'

        echo nya.commitId()
        sh "ls -l repos/nya"
    }
}
