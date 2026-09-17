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

        stage('VERIFY')
        {
            steps
            {
                sh 'pwd'
                sh 'ls -la'
                sh 'git log -1 --oneline'
            }
        }
        stage('test')
        {
            steps
            {
                echo 'ALL TEST ARE DONE!'
            }
        }
    }
}
