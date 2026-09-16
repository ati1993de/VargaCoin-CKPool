# Security Policy

Do not publish wallet seeds, private keys, RPC credentials, `.cookie` files or production configuration.

If a secret is accidentally committed:

1. rotate or revoke it immediately;
2. remove it from repository history;
3. verify whether wallet material was exposed;
4. scan the repository again before publication.

Production VargaCoin node and pool configuration is not part of this repository.
