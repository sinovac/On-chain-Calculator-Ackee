
![School of Solana](https://github.com/Ackee-Blockchain/school-of-solana/blob/master/.banner/banner.png?raw=true)

Welcome to **Task 3** of the **School of Solana Season 6**.

### Task details
Implementing a calculator on-chain. The essential idea behind this on-chain program is to initialize a calculator account with the corresponding update authority. The update authority can change operands inside the calculator (X and Y) as well as change the update authority of the Calculator. Additionally, there are methods such as addition, subtraction, multiplication, and division that will perform overflow/underflow resilient operations and emit the result into the Solana logs. Finally, we will subscribe to the logs in our test suite to check the correctness of the results. **Your task is to understand how the program works on all all parts marked as TODO**.


### Setup
For this Task you need:
- [Rust installed](https://www.rust-lang.org/tools/install)
    - Make sure to use stable version:
    ```bash
    rustup default stable
    ```
- [Solana installed](https://docs.solana.com/cli/install-solana-cli-tools)
    - Use v1.18.18
    - After you have Solana-CLI installed, you can switch between versions using:
    ```bash
    solana-install init 1.18.18
    ```

- [Anchor installed](https://www.anchor-lang.com/docs/installation)
    - Use v0.30.1
    - After you have Anchor installed, you can switch between versions using:
    ```bash
    avm use 0.30.1
    ```

### Commands
With the setup described above, you should be able to run the following commands.

- You should have **Yarn** installed as it is one of the steps during **Anchor** installation, so once you clone the repo, you should be able to run:
```
yarn install
```

- To build the project, run:
```
anchor build
```

- To test the project, run:
```
anchor test
```

## Hints and Useful Links
[Account Context](https://docs.rs/anchor-lang/latest/anchor_lang/derive.Accounts.html)

[Account Model](https://solana.wiki/zh-cn/docs/account-model/)

[Solana Development Course](https://www.soldev.app/course)


-----

### Need help?
>[!TIP]
>If you have any questions, feel free to reach out to us on [Discord](https://discord.gg/z3JVuZyFnp).
