@Library('jenkins-shared-library') _

properties([
    parameters([
        string(name: 'appVersion',defaultValue: '1.0'),
        string(name: 'deploy_to',defaultValue: '')     
    ])
])

def configMap = [
    project  : "roboshop",
    component: "shipping",
    appVersion: (params.appVersion),
    deploy_to: (params.deploy_to)
]

deploy(configMap)