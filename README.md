# pipeline {
#    agent any
#         stages {
#             stage ('git clone') {
#            steps { git branch: 'main', url: 'https://github.com/sekharpadala333/Test.git'
#             }
#         }
#             stage ('test') {
#             steps {echo " this test is good"
#             }
#         }
#             stage ('build') {
#             steps {echo " final buil completed"
#             }
#         }
#     }
