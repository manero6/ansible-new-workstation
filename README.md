# Ansible New Workstation
Ansible plays to set everything up after fresh OS installation.

more info soon ;)

## Before using these Playbooks
### Git stuff

- a SSH key should be there
  - it should be then imported to GitHub, GitLab, etc.
- SSH access to `github.com`, `gists.github.com`, etc. should be established before running the git/gist playbook
  - else ansible will not be able the go beyond the 'key fingerprint' prompt
