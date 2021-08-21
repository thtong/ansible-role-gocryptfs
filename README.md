# thtong.gocryptfs

Installs gocryptfs, encrypted overlay filesystem written in Go, for amd64 Linux. <https://github.com/rfjakob/gocryptfs>

## Requirements

None.

## Role Variables

    gocryptfs_action: install # to remove set to uninstall
    gocryptfs_version: latest # set to specific release for older versions
    gocryptfs_user: set owner of binaries - defaults to ssh user of target host
    gocryptfs_bin_dir: set to destination path of binaries - defaults to /usr/local/bin

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: thtong.gocryptfs }

## License

BSD

## Author Information

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
