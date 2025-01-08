pipeline{
    agent any

    stages{
        stage('Build Amia Dev Module'){
            steps {
                echo 'Building...'
                script{
                    sh 'chmod +x pull-amia.sh'
                    sh './pull-amia.sh'
                    sh './build-dev-mod.sh'
                }
            }
        }

    }
}