node {
    
stage('SCM') {
    steps {
        echo 'Cloning sprint-1 branch'

        git branch: 'sprint-1',
            url: 'https://github.com/AnilReddyKarna/spring-petclinic-new.git'
    }
}


    stage('Build') {
        echo 'Building..'
        // Add build steps here
        sh 'mvn package'
    }

    stage('Test') {
        echo 'Testing..'
        // Add test steps here
        sh 'mvn test'
    }
}
