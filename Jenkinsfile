pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                git branch: 'master', url: 'https://github.com/omminikishore/Test_Work.git/'
            }
        }
        stage('Running Script') {
            steps {
                sh 'chmod +x system_admin.sh'
                sh './system_admin.sh'
            }
        }
    }
}
