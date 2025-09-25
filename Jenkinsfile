node('built-in') 
{
    stage('ContinuousDownload_Master') 
	{
    git 'https://github.com/yankils/hello-world.git'
	}
    stage('ContinuousBuild_Master') 
	{
    sh label: '', script: 'mvn package'
	}
}
