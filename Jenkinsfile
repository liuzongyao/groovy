@Library('zongyao') _

// 在使用 library 里定义的 global variables 的时候，需要 import 
// 而且每一个 import 都需要一个 @Library('balabala') 的注解标注
// 加了 _ 之后，就不需要了

pipeline {
    agent none
    stages {
        stage ('Example') {
            steps {
                // log.info 'Starting' 
                script { 
                    log.info 'Starting'
                    log.warning 'Nothing to do!'
                }
            }
        }
    }
}
