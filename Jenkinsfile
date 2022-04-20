pipeline{
  agent any
  stages{
    stage('clone'){
      steps{
        git branch: 'main', url: 'https://github.com/duongspm/loly-cup-tea.git'
      }
    }
    stage('test')
      {
        steps
        {
          echo 'Testing the application ...'
        }
      }
      stage('deploy')
      {
        steps
        {
          echo 'Deplying the application ...'
          script{
            def test = 2 + 2 > 5 ? 'ngầu' : 'Không ngầu'
            echo test
          }
        }
      }

  }
}
