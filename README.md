# VargaCoin CKPool

VargaCoin CKPool is the VargaCoin-adapted CKPool source tree for SHA-256d solo mining.

> **Status:** development / pre-mainnet publication preparation.
> Development endpoints, ports and configuration examples are not final Mainnet guarantees until the official VargaCoin Mainnet release is announced.

## VargaCoin

- Coin: VargaCoin
- Ticker: VARG
- Proof of Work: SHA-256d
- Mining mode: Solo
- Current DEV / pre-mainnet Stratum endpoint: `pool.vargacoin.com:3370`
- Username / worker: `YOUR_VARG_ADDRESS`
- Password: `x`

Example:

```text
URL:      stratum+tcp://pool.vargacoin.com:3370
Username: YOUR_VARG_ADDRESS
Password: x
```

## Repository purpose

This repository contains the CKPool source adapted for VargaCoin.

It must not contain production secrets or runtime data, including:

- RPC usernames or passwords
- wallet files, seeds or private keys
- `.cookie` authentication files
- production-only configuration
- logs, PID files or backups
- private/internal infrastructure data

## Upstream documentation

The original upstream README is preserved as [`README-UPSTREAM.md`](README-UPSTREAM.md).

Existing upstream copyright and license information remains applicable unless explicitly documented otherwise.

## Security

Never expose the VargaCoin Core RPC interface publicly.

Before publication, review the repository for credentials, wallet material, production paths and internal infrastructure information.

## Mainnet release

The public CKPool repository can be prepared before Mainnet, but Mainnet-specific values should only be documented as final after the VargaCoin Core, wallet, node, DNS and mining configuration have been validated.
