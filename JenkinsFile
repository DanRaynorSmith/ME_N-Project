pipeline{
        agent any
        stages{
            stage('Build'){
                steps{
                    sh '''exit
                    echo ${pwd}
                    git pull origin setup-front-end
                    su - jenkins'''
                    echo "Pipeline successful"
                    }
                }
             stage('Success'){
                steps{
                       echo "Pipeline successful"
                     }
               }
        }
}
