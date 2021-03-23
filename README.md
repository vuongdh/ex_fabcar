# ex_fabcar
cd first-network
sudo ./byfn down

# fabcar
cd ../fabcar
rm -rf wallet
node enrollAdmin.js
node registerUser.js
node apiserver.js
