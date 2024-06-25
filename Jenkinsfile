pipeline {
    agent any

    parameters {
        string(name: 'deployenv', description: 'Name of the person')
        string(name: 'stage_number', description: 'Age of the person')
        string(name: 'CCID', description: 'School of the person')
    }

    stages {
        stage('Echo Parameters') {
            steps {
                script {
                    echo "Name: ${params.deployenv}"
                    echo "Age: ${params.stage_number}"
                    echo "School: ${params.CCID}"
                }
            }
        }
    }
}
