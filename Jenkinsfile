pipeline{
    agent any
    stages{
        parallel{
            stage("Compile"){
            steps{
                echo "Compile completed"
                sleep 3
            }
        }
        stage("Build"){
            steps{
                echo "Build completed"
                sleep 3
            }
        }
        stage("test"){
            steps{
                echo "test completed"
                sleep 3
            }
        }
        stage("deploy"){
            steps{
                echo "deploy completed"
                sleep 3
            }
        }
        }
    }
}
