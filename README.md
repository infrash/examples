# examples.infrash.com

examples of usage infrash scripts 


## Monitoring with docker images and services 

+ Docker with services on many ports
+ File in.csv with list of services and ports


    compare.sh 1/in.csv 1/out.csv 1/status.csv

wejsciowy

    ip_port,https_status
    192.168.0.1:80,200
    192.168.0.1:443,200
    192.168.0.1:8000,200
    192.168.0.1:3000,200

wyjsciowy, wygenerowany przez skrypt bash

    ip_port,https_status
    192.168.0.1:80,200
    192.168.0.1:443,200
    192.168.0.1:8000,200
    192.168.0.1:3000,200


## github-orgs-plesk-domains

build from projects list github organisations and prepare subscription with domain on plesk
