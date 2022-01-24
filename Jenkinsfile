node('built-in') 
{
    stage('Continuous Download_B') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_B') 
	{
    sh label: '', script: 'mvn package'
	}
 }
