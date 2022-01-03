# Public-Key-Infrastructure-PKI-Lab

# Task 1: Becoming a Certificate Authority (CA)
Copy the configuration file into current directory:

      cp /usr/lib/ssl/openssl.cnf ./openssl.cnf 

![task1](https://github.com/muneebimran/Public-Key-Infrastructure-PKI-Lab/blob/f465a1b43a879218f81d455e6ab78ac6e96657ec/Task1/1.png)

what does this comand means

     req	Creates a signing request.
    -new	Creates new requests.
    -x509	Inspects signed certificate by loading x509 modules.
    -keyout	Used to give a path to a filename, where it writes newly created private keys. 
    -out	Specifies the output file where the result will be stored
    -config	Configuration file to be specified. 
create new sub-directories and files

     mkdir PKI
    cp "/usr/lib/ssl/openssl.cnf" "/home/seed/PKI/"
    mkdir demoWK
    cd demoWK
    mkdir certs crl newcerts
    touch 1000 > serial
    gedit index.txt
