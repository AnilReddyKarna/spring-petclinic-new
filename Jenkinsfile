node {
    
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
