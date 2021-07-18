node('master') 
{
    stage('Continuous Download_Master') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous_Master') 
	{
    sh label: '', script: 'mvn package'
    
	}
}
