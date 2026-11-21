# SigmaOS-sigmaos-motor

SigmaOS integration component for **Motor theme**.

## Commands

```bash
sigmaos-sigmaos-motor install   # install package + deploy defaults
sigmaos-sigmaos-motor deploy    # copy config templates to $HOME
sigmaos-sigmaos-motor status    # binary/package/config report
sigmaos-sigmaos-motor reset     # remove deployed config
sigmaos-sigmaos-motor open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
