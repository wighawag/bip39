Restoring your Ethers (ETH or ETC) without a Ledger Nano S

We published a patched version of the original BIP 39 recovery tool to let you recover your Ethers without a Nano S, using your BIP 39 backup seed. You can also use this method to split funds if you mixed ETH/ETC on the same Nano S address.

Make sure you're running the recovery tool on an offline, trusted computer. You'll be exposing your seed which means all applications can be compromised, not just your Ethers. 

After obtaining your private key, you can use any Ethereum wallet to import your funds, such as MyEtherWallet (for both ETH/ETC chains), Jaxx (ETH), Parity (for both ETH/ETC chains) or full nodes such as Geth (for both ETH/ETC chains) ...

The recovery tool is available on this repository : https://github.com/btchip/bip39/tree/ledger-ethereum

Clone the repository or download the standalone file bip39-standalone.html

You can then open this page and enter your recovery seed.

To obtain your ETH private key : select Ethereum in the Coin menu, and read the first derived private key (m/44'/60'/0'/0)

To obtain your ETC private key (Chrome app above 1.0.5) : select Ethereum Classic (Ledger transitional 1.0.5) in the Coin menu, and read the first derived private key (m/44'/60'/160720'/0'/0)

If you used the Chrome application before 1.0.5, the ETC private key is the same as the ETH private key. You can use this method to recover the private key, and use MyEtherWallet to split the funds to a new address generated from a new seed.

Note that MyEtherWallet expect your private key to be entered without the leading "0x" - to use it, go into the "Send Ether" tab, copy & paste its value, and select "Unlock Wallet"
