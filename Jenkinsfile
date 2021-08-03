pipeline {
    agent any

    parameters {
        string(name: '我是pipeline参数', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
    }    
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.我是pipeline参数}"
            }
        }
    }
    
    // stages {
    //     stage('Example') {
    //         input {
    //             message "Should we continue?"
    //             ok "Yes, we should."
    //             submitter "alice,bob"
    //             parameters {
    //                 string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
    //             }
    //         }
    //         steps {
    //             echo "Hello, ${PERSON}, nice to meet you."
    //         }
    //     }
    // }
}
