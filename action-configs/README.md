# GitHub Action Configurations

This directory contains configuration files used by GitHub Actions in this repository. These files help define and customize the behavior of workflows, enabling reusable and centralized configuration management.

## Usage

Reference these configuration files from your workflow YAML files to drive action usage and settings.

## Structure

- Each file in this directory serves a specific purpose for different actions or workflows.
- Update or add new configuration files as needed to support additional workflows.

### repo-sync.yml

This file contains a list of source and destination repositories that are used to sync repositories into this organization. The configuration defines:

- **source**: The original repository to sync from (format: `owner/repo-name`)
- **target**: The destination repository in this organization (format: `jamestrichardson/repo-name`)
- **visibility**: Repository visibility setting (public/private, defaults to private)
- **disable-github-actions**: Whether to disable GitHub Actions in the synced repo (defaults to true)
- **archive-after-sync**: Whether to archive the repository after syncing (defaults to false)

## Contribution

Feel free to modify or extend these configuration files to fit your workflow requirements.
