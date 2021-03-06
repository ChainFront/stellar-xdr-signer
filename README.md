# Stellar XDR Transaction Signer

This repo contains a simple golang program to sign an XDR transaction for the Stellar network.

## Building

    make clean build

## Usage

In order to first generate an XDR encoded transaction you can use the [Stellar Laboratory](https://www.stellar.org/laboratory/#?network=public).

Then use this utility to sign the transaction, by running the following:

    ./stellar-tx-signer --xdr <Base64 Encoded XDR String>
    
This will prompt you for the seed necessary to sign the transaction.

You can then submit the signed transaction to the Stellar Network [here](https://www.stellar.org/laboratory/#explorer?resource=transactions&endpoint=create&network=public).


