stage('init') {
    node {
        sh 'echo "cd /opt/tikal/deploy; ./deploy.sh init"'
    }
}
stage('reqs') {
    node {
        sh 'echo "cd /opt/tikal/deploy; ./deploy.sh reqs"'
    }
}
stage('vagrant') {
    node {
        sh 'echo "cd /opt/tikal/deploy; ./deploy.sh vagrant"'
    }
}
stage('server') {
    node {
        sh 'echo "cd /opt/tikal/deploy; ./deploy.sh server"'
    }
}
stage('pubkey') {
    node {
        sh 'echo "cd /opt/tikal/deploy; ./deploy.sh pubkey"'
    }
}
stage('net') {
    node {
        sh 'echo "cd /opt/tikal/deploy; ./deploy.sh net"'
    }
}
stage('base') {
    node {
        sh 'echo "cd /opt/tikal/deploy; ./deploy.sh base"'
    }
}

