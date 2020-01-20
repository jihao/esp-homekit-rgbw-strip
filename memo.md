git submodule update --init --recursive

cd components/esp-homekit-common-functions 
git pull 
git checkout dev

git add components/esp-homekit-common-functions 
git commit -m "update submodule components/esp-homekit-common-functions "