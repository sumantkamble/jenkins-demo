library identifier: 'pipeline-libs@main', retriever: modernSCM([$class: 'GitSCMSource', remote: 'https://github.com/sumantkamble/pipeline-libs.git'])

node {
    checkout scm
    pipelineSettings.stages.eachWithIndex { stage, i ->
        def performOfflineTests = i == 0
        sayHello("Sumant")
    }
}
