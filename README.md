# ex_fabcar
cd first-network
sudo ./byfn down

# fabcar
cd ../fabcar
rm -rf wallet

# javascript

cd javascript 
node enrollAdmin.js
node registerUser.js
node apiserver.js


# remove image
cd ../../first-network
sudo ./byfn down

# test
## get all
http://127.0.0.1:8080/api/queryallcars

## get one
http://127.0.0.1:8080/api/query/CAR4

## post
http://127.0.0.1:8080/api/addcar

{
    "carid": "CAR12",
    "make": "Honda",
    "model": "Accord",
    "colour": "black",
    "owner": "Tom"
}