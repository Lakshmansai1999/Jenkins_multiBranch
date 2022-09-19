node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/Lakshmansai1999/maven.git'
	}
    stage('Continuous Build') 
	{
    sh 'mvn package'
	}
}
