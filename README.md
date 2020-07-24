# bash-function

function doco() {
        docker-compose -p $1 up
}

function runGesco(){
        cd www/contact_europe_gesco/docker
        doco gesco
}

function runMd(){
        cd www/contact_europe_masterdata/docker
        doco masterdata
}

function install(){
        sudo apt-get install $1
}
