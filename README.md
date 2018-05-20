I set this up with multiple GitHub accounts and multiple SSH keys. It's actually not that hard but there are some things to remember.

1. Follow https://coderwall.com/p/7smjkq/multiple-ssh-keys-for-different-accounts-on-github-or-gitlab for setting up the SSH keys.
2. Since I configured the hostname for the Metatris account key to be github.com-metatris, whenever I add a remote to an existing repo I have to replace `git@github.com` with `git@github.com-metatris`. Then it all works.
