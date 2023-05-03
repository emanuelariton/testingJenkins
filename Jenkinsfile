pipeline {

    agent any

    stages {

        stage("build") {

            steps {
                echo 'building stage'
                
                script{
                    def test = 2 + 2 > 3 ? 'cool' : 'not cool'
                }
            }
        }

        stage("test") {

            steps{
                echo 'test stage'
            }

        }

        stage("deploy") {

            steps{
                echo 'deploying stage'
            }

        }
    }
}

// node {
//     //groovy script
// }
