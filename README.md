# Ansible New Workstation
Ansible plays to set everything up after fresh OS installation.

more info soon ;)

## Before using these Playbooks
### Git stuff

- if cloning with SSH
  - a SSH key should be there (else import one or create a new one with `ssh-keygen`)
    - if the key is new, then it should be imported to GitHub, GitLab, etc.
  - SSH access to `github.com`, `gist.github.com`, etc. should be established before running any git/gist playbook
    - else ansible will not be able the go beyond the 'key fingerprint' prompt
