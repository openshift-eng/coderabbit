# OpenShift Engineering CodeRabbit Configuration

This repository contains the organization-wide [CodeRabbit configuration](https://docs.coderabbit.ai/configuration/central-configuration) for the `openshift-eng` GitHub organization.

Rules and instructions defined here apply to most openshift-eng repositories. Repository-specific overrides can be added in each repo's own `.coderabbit.yaml`.

## How it works

Repositories without their own `.coderabbit.yaml` automatically use this org-wide configuration. If a repository needs to add repo-specific settings, it must set `inheritance: true` in its `.coderabbit.yaml` to merge with the org-wide defaults — otherwise the repo-level config fully replaces them.

```yaml
inheritance: true
```
