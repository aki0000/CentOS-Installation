# OS-Installation-For-RPI
### Prerequisite
If your microsSD had been used, need to erase data on it.

MaOS: Disk Utility > External > Erase

x < 32GB: MS-DOS(FAT)
64GB < x: exFAT

### Execute tasks
ansible-playbook site.yaml -vvv --ask-become-pass --extra-vars="file={file path}" 