#!groovy

node {
    stage ('checkout!!!') {
        checkout scm
    }
    stage ('build') {
        echo "build"
        sleep 2
    }
    stage ('test') {
        echo "test"
        sleep 1
    }
    stage ('staging') {
        echo "staging"
        sleep 4
    }
    stage ('production') {
        echo "production"
        sleep 5
    }
}
