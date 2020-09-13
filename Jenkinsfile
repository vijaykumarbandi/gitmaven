pipeline {
agent any
stages {
stage('compile stage') {
steps {
withMaven(maven : 'M2_Home') {
sh 'mvn complie'
}
}
}
}
}
