# SSH public keys — cmardikas

My public SSH keys for administrators to use when granting me access to servers.

These files are published for distribution only, not for GitHub authentication.

## Current key

| File | Description |
|---|---|
| [ssh.pub](./ssh.pub) | YubiKey-backed SSH key, type `sk-ssh-ed25519@openssh.com` |

## Verify before granting access

Contact me through an established, trusted channel to confirm the key's SHA-256 fingerprint before installing it.

To display the downloaded key's fingerprint:

```bash
ssh-keygen -lf ssh.pub -E sha256
```

## Key changes

Please confirm changes with me before replacing an installed key or adding a new one. Do not automatically trust new keys simply because they appear in this repository.

Removing a key from this repository does not remove it from servers where it has already been installed.
