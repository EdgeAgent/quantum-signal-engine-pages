# QuantumSignal Engine Showcase

Public static showcase for [QuantumSignal Engine](https://github.com/EdgeAgent/quantum-signal-engine), a private local-first crypto intelligence and paper-trading research engine.

This repository contains presentation content only. It does not contain exchange credentials, wallet secrets, execution code, or the private engine source. The live Python/WebSocket dashboard remains local and paper-only.

## GitHub Pages

Configure **Settings → Pages → Deploy from a branch → `main` → `/docs`**.

The expected project-site URL is:

`https://edgeagent.github.io/quantum-signal-engine-pages/`

## Local preview

```bash
python3 -m http.server 8870 --directory docs
```

Then open `http://127.0.0.1:8870/`.
