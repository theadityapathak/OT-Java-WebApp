node {
    properties([[$class: 'JiraProjectProperty'], parameters([choice(choices: ['clean', 'install'], description: '', name: 'opts')])])
               stage ("build"){             
               sh "mvn ${opts}"
            }
}
