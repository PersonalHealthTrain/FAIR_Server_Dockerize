# How to dockerize HAPI FHIR server? 
    Step 1: $ sudo git clone https://rezacsedu@bitbucket.org/rezacsedu/hapi_fhir_dockerize.git
    Step 2: $ cd hapi_fhir_dockerize
    Step 3: $ sudo docker build -t jetty .
    Step 4: $ sudo docker run -p 8080:8080 -d jetty
    Step 5: Access the server with GET/POST at <server_url>:8080/baseDstu3 and see sample patient records at <server_url>:8080/baseDstu3/Patient
