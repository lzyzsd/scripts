# scripts
配置各种开发环境的脚本

配置Node.js环境
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.26.1/install.sh | bash
export NVM_IOJS_ORG_MIRROR="http://npm.taobao.org/mirrors/iojs"
nvm install v3.3.0
nvm alias default v3.3.0
npm install -g cnpm --registry=https://registry.npm.taobao.org
cnpm install pm2 -g
```
