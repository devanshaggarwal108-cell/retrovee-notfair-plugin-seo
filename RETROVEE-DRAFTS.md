# Retrovee draft workflow

This edition builds on [tmenov/notfair-plugin-seo](https://github.com/tmenov/notfair-plugin-seo). Original copyright and licensing are in [LICENSE](LICENSE).

Upstream main branch ZIP SHA-256: `bc2d9d654f8aa388be4839805fdaf6bcd3eb1dc6369fc641e616b2d6ac33cb5f`.

Use the [`retail-search-console-review` skill](codex-skills/retail-search-console-review/SKILL.md) for the Codex draft workflow. Copy the entire skill directory into your Codex skills directory. This skill has no runtime dependencies. The upstream tools retain their separate setup instructions in the original README.

Keep credentials, customer data and performance exports out of Git. Review proposed external changes and get approval before making them live.

## GitHub Actions

The original workflows are retained in `.github/upstream-workflows/` for review. Enable selected workflows only after checking their triggers, tokens and publish targets.
