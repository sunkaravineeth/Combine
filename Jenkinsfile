pipeline{
    agent any
    stages{
        stage("dependent jobs"){
            parallel{
                stage("Compile"){
                    steps{
                        echo "Compile"
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
