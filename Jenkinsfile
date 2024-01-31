node('built-in')
{
        stage('ContinuousDownload')
        {
                try 
                {
                    git 'https://github.com/intelliqittrainings/maven.git'
                }
                catch(Exception e1)
                {
                    
                }
                
        }
        
        stage('Continuous Build')
        {
            try {
                sh 'mvn package'
            }
            
            catch(Exception e2)
            {}
        }


}
