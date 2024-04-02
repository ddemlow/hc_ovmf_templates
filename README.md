#HyperCore Customized OVMF Template VMs

VM templates created on Hypercore 9.3.5 for UEFI and VTPM virtual machines which are now custimized with the following:

    - Secure Boot Disabled
    - Default resolution set to 1024x768

Templates have no virtual disk.  After VM import one must be created and set to boot (or a cloud-image uploaded, attached to VM and set to boot)

These template folders can be moved to an SMB share and imported into HyperCore using normal UI or API / Ansible based VM import, or you can attempt direct import from this repository using REST API or ansible.

see import_templates.yml for example of ansible play book to import template directly from this repo