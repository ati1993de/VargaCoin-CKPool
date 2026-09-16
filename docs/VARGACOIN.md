# VargaCoin CKPool notes

## Mining

VargaCoin uses SHA-256d proof of work.

Current DEV / pre-mainnet Solo Stratum endpoint:

```text
pool.vargacoin.com:3370
```

Miner credentials:

```text
Username: YOUR_VARG_ADDRESS
Password: x
```

The miner username is the payout address. Never use a private key, seed phrase or wallet password as Stratum credentials.

## RPC

CKPool should communicate with VargaCoin Core over a trusted local or private interface.

Public documentation must use placeholders such as:

```text
RPC_HOST
RPC_PORT
RPC_USER
RPC_PASSWORD
```

Do not publish real RPC credentials, `.cookie` files, wallet material or production secrets.

## Mainnet

Mainnet-specific chain parameters, ports, seeds, checkpoints, genesis information and release tags must be taken from the final verified VargaCoin Core release.
