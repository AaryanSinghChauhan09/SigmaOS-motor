# SigmaOS-motor

SigmaOS integration component for **Motor theme**.

## Commands

```bash
sigmaos-motor install   # install package + deploy defaults
sigmaos-motor deploy    # copy config templates to $HOME
sigmaos-motor status    # binary/package/config report
sigmaos-motor reset     # remove deployed config
sigmaos-motor open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
