pipeline{

    agent any

    stages{
        stage('Build'){
            steps{
                echo "Building....."
                withMaven {
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