pipeline{

    agent any

    stages{
        stage('Build'){
            steps{
                echo "Building....."
                withMaven(maven: 'maven_3_8_6'){
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