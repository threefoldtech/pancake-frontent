# 🥞 Pancake Frontend

This project contains the swap features of the pancake application.

##install requirements
sudo apt install xsel
needs nodejs 12.x+ (tested with 14.x)


in case of ubuntu install newest YARN

sudo apt remove cmdtest

sudo apt remove yarn

curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -

echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list

sudo apt-get update

sudo apt-get install yarn -y


##install app

git clone https://github.com/threefoldtech/pancake-frontent.git

yarn install

yarn build

yarn integration-test

localhost:3000


## Documentation pancakeswap

- [Info](doc/Info.md)
- [Cypress tests](doc/Cypress.md)
