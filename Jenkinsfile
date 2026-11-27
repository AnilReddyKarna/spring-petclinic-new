node {

    stage('SCM') {
        echo 'Cloning sprint-1 branch'

        //git branch: 'sprint-1',
        git url: 'https://github.com/AnilReddyKarna/spring-petclinic-new.git'
    }

    stage('Build') {
        echo 'Building Spring PetClinic...'

        sh 'mvn clean package'
    }

    stage('Test') {
        echo 'Running Unit Tests...'

        sh 'mvn test'
    }
}

