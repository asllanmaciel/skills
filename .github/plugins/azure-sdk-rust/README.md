# azure-sdk-rust

Azure SDK patterns and best practices for Rust developers. Covers 7 skills spanning identity, Key Vault, storage, Cosmos DB, and Event Hubs.

## Install

Install an individual skill with the skills CLI:

```bash
npx skills add https://github.com/microsoft/skills/tree/main/.github/plugins/azure-sdk-rust/skills/azure-identity-rust
```

Or install the full plugin:

```
/plugin install azure-sdk-rust@skills
```

## Skills

| Skill | Package / Focus |
|-------|----------------|
| `azure-cosmos-rust` | Cosmos DB |
| `azure-eventhub-rust` | Event Hubs |
| `azure-identity-rust` | Identity / Authentication |
| `azure-keyvault-certificates-rust` | Key Vault Certificates |
| `azure-keyvault-keys-rust` | Key Vault Keys |
| `azure-keyvault-secrets-rust` | Key Vault Secrets |
| `azure-storage-blob-rust` | Blob Storage |
