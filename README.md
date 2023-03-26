# ganache_eth-brownie

## Description
Study repository for soot using ganache cli and eth-brownie.

## Setup
1. build image & run container by docker-compose
`$ docker-compose up -d --build`
2. Clone https://github.com/PatrickAlphaC/erc20-brownie.git and run it
`$ git clone https://github.com/PatrickAlphaC/erc20-brownie`
`$ brownie run scripts/1_deploy_token.sol`

If you don't install docker in your machine please install by [here](https://docs.docker.com/engine/install/) or just run 
`$ curl -fsSL https://test.docker.com/ | sh`
