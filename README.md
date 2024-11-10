# Note
Original code repo:https://github.com/kodekloudhub/course-jenkins-project
Additions made:
  - Jenkinsfile

# Purpose
- This repo contains a sample web application written in Python the goal was to automate the test build and deploy process using Jenkins
- Deployment is made to an aws ec2 instances
- The provided Jenkinsfile pipeline is separated into the following stages
  . Check out the code.
  . Install the dependencies from the requirements.txt file on a new venv.
  . run unit tests.
  . build code.
  . Deploy code as a system service on the ec2 instance.
