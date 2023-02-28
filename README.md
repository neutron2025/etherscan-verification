# Sample Hardhat Project



```shell
mkdir etherscan-verification
cd etherscan-verification
npm init --yes
npm install --save-dev hardhat
npx hardhat

contracts目录下创建 Verify.sol
npm install dotenv
创建 .env文件配置
QUICKNODE_HTTP_URL="add-quicknode-http-provider-url-here"

PRIVATE_KEY="add-the-private-key-here"

POLYGONSCAN_KEY="polygonscan-api-key-token-here"

修改scripts/deploy.js

修改 hardhat.config.js 



npm install @nomicfoundation/hardhat-toolbox
编译运行 npx hardhat compile

上链 npx hardhat run scripts/deploy.js --network mumbai

```
