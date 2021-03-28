# homebrew-tap

Add this tap to [HomeBrew](https://brew.sh) using.

`brew tap iain2k/tap`

## Formula

**sshpass** 

This formula installs [sshpass](http://sourceforge.net/projects/sshpass) as HomeBrew disables this Formula for valid security reasons.  I use it purely to bootstrap hosts using [Ansible](https://ansible.com) and the `-k` option.

```
brew -v install sshpass                                        
==> Searching for similarly named formulae...
Error: No similarly named formulae found.
Error: No available formula or cask with the name "sshpass".
We won't add sshpass because it makes it too easy for novice SSH users
to ruin SSH's security.
```

You can then install sshpass using brew.

`brew -v install sshpass`


