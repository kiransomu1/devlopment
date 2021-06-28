node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/kiransomu1/devlopment.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}	
