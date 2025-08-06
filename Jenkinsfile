pipeline {
    agent any

    stages {
        stage('Clonar repo') {
            steps {
                git 'https://github.com/TestingDaniel/mi-primer-devops.git'
            }
        }

        stage('Compilar') {
            steps {
                echo 'Compilando...'
            }
        }

        stage('Pruebas') {
            steps {
                echo 'Ejecutando pruebas...'
            }
        }

        stage('Despliegue') {
            steps {
                echo 'Desplegando aplicación...'
            }
        }
    }
}
