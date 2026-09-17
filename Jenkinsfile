pipeline
{
    agent any

    stages
    {
        stage('CHECKOUT')
        {
            steps
            {
                checkout scm
            }
        }

        stage('READ')
        {
            steps
            {
                sh 'cat app.txt'
            }
        }
        stage('MODIFY')
        {
            steps
            {
               sh 'echo "BUILD HANDLED BY JENKINS!" >> app.txt'

                sh 'cat app.txt'
            }
        }
    }
}
