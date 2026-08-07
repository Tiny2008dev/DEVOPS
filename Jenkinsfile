pipeline {
    agent any
    stages{
        stage("Hello"){
            steps {
                echo "Hello Devam!"
            }
        }
        stage("Bye"){
            steps {
                echo "bye devam"
            }
        }
    }

POST {
    success{
        echo"pipeline executed "
    }
    failure {
        echo "pipelibe failed"
    }
}
}
