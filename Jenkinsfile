pipeline{

    agent any

    stages{
        stage('Build'){
            steps{
                echo "Building....."
                withMaven(maven: 'maven_3_5_0'){
                    sh 'mvn clean package'
                }
            }
        }

        stage('Deploy'){
            steps{
                echo ".......Deploying......."
            }
        }

    }


}