# Purge sensitive files from git repository

## Secure process

1. Ask everyone to commit theirs changes and to remove their repository
2. `git clone <repo> /tmp/repo`
2. `cd /tmp/repo && purge <pattern>`
3. Ask everyone to clone the repository

The pattern can be
- '*password.txt'
- 'config/*.txt'
