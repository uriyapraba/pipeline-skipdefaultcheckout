pipeline
{
    agent none
    stages
    {
        stage('skipdefaltcheckout')
        {
            agent any
            options
            {
                skipDefaultCheckout()
            }
            steps
            {
                echo "Hello World"
            }
        }
    }
}