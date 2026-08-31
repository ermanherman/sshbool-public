# SSHBool — release downloads

Built binaries only. The source lives in a separate private repository.

## Download

Grab the latest `.exe` from [Releases](../../releases/latest). It is a single
portable file — no installer, no extra DLLs. Copy it anywhere and run it.

## Updating

SSHBool checks this repository for new versions. In the app:

**Settings › Updates › Update manifest URL**

```
https://github.com/ermanherman/sshbool-public/releases/latest/download/latest.json
```

Every release is signed, and the app refuses any download that does not verify
against its built-in public key.
