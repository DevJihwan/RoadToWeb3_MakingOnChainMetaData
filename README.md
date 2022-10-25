[개발순서]
========
    * npx hardhat init (프로젝트 생성)
        * ❗️ README.md가 있으면 생성이 안됨. 
    * ChainBattle.sol 작성 
    * Alchemy 에서 Polygon mumbai network project 생성
    * .env 파일작성
    

[npm module]
============
    
    * npm add @openzeppelin/contracts
    * npm install dotenv --save
    * npm install --save-dev @nomiclabs/hardhat-waffle 'ethereum-waffle@^3.0.0' @nomiclabs/hardhat-ethers 'ethers@^5.0.0'


[hardhat 명령어]
==============
    * npx hardhat compile
    * npx hardhat run scripts/deploy.js --network mumbai
    * npx hardhat verify --network mumbai <YOUR_SMARTCONTRACT_ADDRESS>
    * npx hardhat verify --network mumbai 0xbF64135700AC4927dAa6dA84E3d8958cBb704d0e
