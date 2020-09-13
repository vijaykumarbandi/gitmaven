pipeline {
agent any
stages {
stage('compile stage') {
steps {
withEnv(maven : 'M2_Home') {
sh 'mvn complie'
}
}
}
}
}
