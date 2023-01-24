@Library('global-jenkins-library@2.1.1') _

node('docker') {
    buildInfo = getBuildInfo()
    buildSimpleDocker_v3(
        buildInfo: buildInfo,
        imageprivacy: 'private',
        dockerImageRepositoryName : 'netstats'
    )
}