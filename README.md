KernelCi Storage
================

This is the Ansible configuration to deploy/setup the kernelci-storage
system at:

    https://github.com/kernelci/kernelci-storage

Requirements
############

Ansible >= 2.0

In order to run the entire configuration, some "secrets" are necessary.
Put them in a YAML file, and pass it to Ansible as:

    -e "@/path/to/file/secrets.yml"

To skip the secrets taks, just pass:

    --skip-tags=secrets

