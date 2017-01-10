
node {
stage('Build') {
    sh 'echo hello world'
    checkout scm
    dir ('./build')
    sh 'ant -f ./build.xml'
}
}