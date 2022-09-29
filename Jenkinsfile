pipeline{
    agent any
    stages {
        stage("one"){
            steps{
                echo "hello world"
            }
        }
        stage("two"){
            steps{
                git 'https://github.com/Trackft6pm/hello-world.git'
            }
        }
        stage("three"){
            steps{
                echo "welcome"
            }
        }
    }
}
