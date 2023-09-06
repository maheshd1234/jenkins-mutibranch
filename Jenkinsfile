node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/maheshd1234/maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
