pipeline{
    agent any
    stages{
        stage("dependent jobs"){
            parallel{
                stage("Compile"){
                    steps{
                        echo "Compile"
                    }
                    steps{
                        echo "Compile1"
                    }
                    steps{
                        echo "Compile2"
                    }
                }
                stage("build"){
                    steps{
                        echo "build"
                    }
                }
                stage("test"){
                    steps{
                        echo "test"
                    }
                }
                stage("deploy"){
                    steps{
                        echo "deploy"
                    }
                }
            }
        }
    }
}
