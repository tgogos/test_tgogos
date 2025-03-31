pipeline {
    agent {
        node {
            label 'dev-server'
        }
    }

    stages {
        stage("Build_Docker_Images"){
            steps {
                echo "***** Building Docker Image *****"
            }
        }


        // *************************
        // ***  UNIT TEST STAGE  ***
        // *************************
        stage("Unit_Tests"){
            steps {
                echo "***** Running Unit Tests *****"
            }
        }
    }
}
