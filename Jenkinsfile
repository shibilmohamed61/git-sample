pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                deleteDir()
                sh '''
                  git clone https://github.com/shibilmohamed61/git-sample.git
                    ls -l
                '''
            }
        }
        stage('deploy'){
            steps{
                sh '''
                    cp -r git-sample/* /var/www/html
                    ls -l /var/www/html
                '''
                    
            }
        }
        
    }
}
