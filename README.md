# Broker Action Vault Revoke V2

This action calls the Vault API to revoke the token. See: [Vault API - Revoke a token (Self)](https://developer.hashicorp.com/vault/api-docs/auth/token#revoke-a-token-self)

# Broker Documentation

Please refer to the [NR Broker Repository](https://github.com/bcgov-nr/nr-broker) for full usage details.

# Usage

<!-- start usage -->
```yaml
- uses: bcgov-nr/action-broker-vault-revoke@v2
  with:
    # The vault token to revoke
    vault_token: ''

    # The vault url.
    # Default: https://knox.io.nrs.gov.bc.ca
    vault_url: ''
```
<!-- end usage -->

# License

The scripts and documentation in this project are released under the [Apache License](LICENSE)

