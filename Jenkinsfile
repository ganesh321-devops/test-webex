pipeline {
    agent any

    parameters {
        string(name: 'name', defaultValue: 'John Doe', description: 'Name of the person')
        string(name: 'age', defaultValue: '25', description: 'Age of the person')
        string(name: 'school', defaultValue: 'ABC University', description: 'School of the person')
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
