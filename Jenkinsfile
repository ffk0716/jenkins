#!groovy

pipeline
{
    agent any 
    stages
    {
        stage('abc')
        {
            steps
            {
                sh 'ls'
            }
        }
        stage('jijeowfejo')
        {
            steps
            {
        parallel firstBranch: {
                sh 'echo $BRANCH_NAME'
    }, secondBranch: {
                sh 'ls'
    }
            }
        }
        stage('jeowfejo')
        {
            steps
            {
                sh 'pwd'
            }
        }
    }
}
