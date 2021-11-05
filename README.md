# simplenodeapp
### getting started

```bash
# add the NodeSource yum repository to your system:
curl -sL https://rpm.nodesource.com/setup_12.x | sudo bash -

# install node.js 12.x and npm
sudo yum install -y nodejs

# check version of node and npm
node --version
npm --version

# setup a new package
npm init

# add mocha for testing
npm install mocha --save-dev