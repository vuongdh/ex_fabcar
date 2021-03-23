# ex_fabcar
cd first-network
sudo ./byfn down

# fabcar
cd ../fabcar
rm -rf wallet
cd javascript
node enrollAdmin.js
node registerUser.js
node apiserver.js


# remove image
cd ../../first-network
sudo ./byfn down