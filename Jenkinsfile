node('built-in') 
{
    stage('ContinuousDownload_Loans') 
	{
    git 'https://github.com/yankils/hello-world.git'
	}
    stage('ContinuousBuild_Loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
