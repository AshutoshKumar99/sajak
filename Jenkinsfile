node('master')
{
    
    stage('Project Name')
    {
        echo 'XBEC'
    }
    
    stage('Checkout code')
    {
        git 'https://github.com/AshutoshKumar99/sajak.git'
    }
    
    stage('Build code')
    {
        bat 'mvn clean install'
    }
    
    stage('JUnit')
    {
        junit 'target/surfire-reports/*.xml'
    }
    
}
