# CodeIgniter Encrypted Env

Optional AES-256-GCM encryption for environment configuration values.

## Status

Early development version. Not production ready.

## Security

- AES-256-GCM authenticated encryption
- Random 12-byte IV
- 16-byte authentication tag
- Versioned `enc:v1:` payload
- Keep encryption keys outside the repository

## Roadmap

- CodeIgniter DotEnv integration
- PHPUnit tests
- CLI encryption commands
- Secure key management documentation
- CI compatibility testing
# codeigniter4-encrypted-env
