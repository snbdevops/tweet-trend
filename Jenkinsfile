pipeline {
    agent {
        node {
            label 'maven'
        }
    }
environment {
    PATH = "/usr/bin:$PATH"
}
    stages {
        stage("build"){
            steps {
                 echo "----------- build started ----------"
                sh 'mvn clean deploy'
                 echo "----------- build complted ----------"
            }
        }
        }
}
