
node {
stage('Build') {
    sh 'echo hello world'
    checkout scm
    sh 'cd build;ant'
    step([$class: 'CheckStylePublisher', canComputeNew: false, defaultEncoding: '', healthy: '', pattern: '**/checkstyle_report.xml', unHealthy: ''])
}
}