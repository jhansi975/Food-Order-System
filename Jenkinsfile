pipeline {
    agent any 

    stages{

        stage("BuildCode"){
            steps {
                sh """
                    cd food_order
                    ant clean
                    ant jar
                
                """
            }
        }
    }
}