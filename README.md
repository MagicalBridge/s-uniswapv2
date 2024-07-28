# SUniswapV2, a clone of UniswapV2 made in educational purposes

## Using this repo

1. `git clone git@github.com:MagicalBridge/s-uniswapv2.git`
2. Ensure you have installed Rust and Cargo: [Install Rust](https://www.rust-lang.org/tools/install)
3. Install Foundry:
   `cargo install --git https://github.com/gakonst/foundry --bin forge --locked`
4. Install dependency contracts:
   `git submodule update --init --recursive`
5. Run tests:
   `forge test`

## Blog posts

1. [Part 1](https://learnblockchain.cn/article/8864), architecture of UniswapV2, adding liquidity, first tests in Solidity, removing liquidity.