node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}
node {
    stage ('Get approval'){
        input "Deploy to prod?"
        
    }
    
    node {
    stage ('deploy to prod'){
        echo "deploying to prod"
    }
}
