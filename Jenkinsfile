pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/MayurNanaware/ITIN_Devops_Lab'
            }
        }

        stage('Run System Info Script') {
            steps {
                // Execute the shell script
                sh './script.sh'
            }
        }
    }
}

