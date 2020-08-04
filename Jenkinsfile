properties([parameters([choice(choices: 'master\properties([[$class: 'GithubProjectProperty', displayName: '', projectUrlStr: 'https://github.com/Jagadeeshs1687/FlightBookingSystem.git/'], parameters([choice(choices: 'master\ndev\nrelease', description: '', name: 'branch')])])   
   node{
      
      stage('Scm Checkout') {
          
          
          echo "pulling the changes from the branch ${params.branch}"
          git url: 'https://github.com/Jagadeeshs1687/FlightBookingSystem.git' , branch:"${params.branch}"
           }
       } }

