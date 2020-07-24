# bash-function

## docker compose
* function doco() {
*        docker-compose -p $1 up
* }

## run gesco
* function runGesco(){
*        cd www/contact_europe_gesco/docker
*        doco gesco
* }

## run masterdata
* function runMd(){
*        cd www/contact_europe_masterdata/docker
*       doco masterdata
* }

## install
* function install(){
*        sudo apt-get install $1
* }
