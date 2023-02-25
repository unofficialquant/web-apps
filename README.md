# Repo Template

Template repo with commitlint, semantic release and github actions setup.

## GitHub Actions

### Dependabot

Dependabot update for GitHub Actions and `npm` are enabled by default. Please refer to the original [documentation](https://docs.github.com/en/code-security/dependabot/dependabot-version-updates/configuration-options-for-the-dependabot.yml-file) for all available configuration options.

```yaml
# Go
- package-ecosystem: gomod
  target-branch: main
  directory: /
  schedule:
    interval: daily

# Python
- package-ecosystem: pip
  target-branch: main
  directory: /
  schedule:
    interval: daily
```
