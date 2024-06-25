pipeline {
    agent any

    parameters {
        string(name: 'name', description: 'Name of the person')
        string(name: 'age', description: 'Age of the person')
        string(name: 'school', description: 'School of the person')
    }

    stages {
        stage('Echo Parameters') {
            steps {
                script {
                    echo "Name: ${params.name}"
                    echo "Age: ${params.age}"
                    echo "School: ${params.school}"
                }
            }
        }
    }
}
