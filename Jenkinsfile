pipeline {

agent any

stages {

stage('Build master'){

when{

branch 'master'

}

steps {

echo "Building maser"

}

}

stage('Build dev'){

when{

branch 'dev1'

}

steps {

echo 'Building dev'

}

}

}

}

