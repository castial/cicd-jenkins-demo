pipeline{

    agent any

    stages{
        stage('Build'){
            steps{
                echo "Building....."
                withMaven(maven: 'maven-3.8.6'){
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