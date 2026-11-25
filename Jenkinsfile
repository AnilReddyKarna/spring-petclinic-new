node {
    stage('SCM') {
        echo 'git clone'
        // Add build steps here
        git 'https://github.com/spring-projects/spring-petclinic.git'
    }

    stage('Build') {
        echo 'Building..'
        // Add build steps here
        sh 'mvn clean package'
    }

    stage('Test') {
        echo 'Testing..'
        // Add test steps here
        sh 'mvn test'
    }
}
