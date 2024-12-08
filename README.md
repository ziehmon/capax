## GitHub Actions

The following configurations only impact GitHub Actions and might require change over time:

- GitHub secret `SSH_PRIVATE_KEY`, contains private SSH key that is templated into `id_rsa` at runtime

- Repository file `./known_hosts`, public SSH key signature of crackhouse used by Ansible/SSH for host checking
 