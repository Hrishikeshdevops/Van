node('built-in') 
{
    stage('Continuous Master Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Master Build') 
	{
    sh label: '', script: 'mvn package'
	}



}
