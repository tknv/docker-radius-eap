# docker-radius-eap
Testing radius eap

Build image  
`docker build -t my-radius-image -f Dockerfile .`  

Run  
`docker run --rm --name my-radius -t -p 1812-1813:1812-1813/udp my-radius-image -X`  

Test  
`$ radtest bob test 127.0.0.1 0 symbol123`  






