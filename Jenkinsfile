node('built-in')

{

stage('ContinuousDownload_test')
         {
    git 'https://github.com/sunildevops77/maven.git'
        }

stage('Continuousbuild_test')
         {
   sh label: '', script: 'mvn package'
        }

}
