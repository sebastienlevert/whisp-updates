# Security

Whisp updates use unauthenticated HTTPS downloads from this public GitHub Releases feed. The application does not contain or send a GitHub credential.

Before publication, release tooling refuses unexpected repository ownership or visibility, dirty or mismatched source, duplicate tags/assets, failed tests/builds, personal-data/model/debug artifacts, and unsupported signing claims. Each release includes source commit/tree provenance and SHA-256 asset hashes.

Do not report private transcripts, audio, settings, tokens, model files, or other personal data in this public repository.
