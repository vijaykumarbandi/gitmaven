pipeline {
agent any
stages {
stage('compile stage') {
steps {
withEnv('M2_Home') {
sh 'mvn complie'
}
}
}
}
}
