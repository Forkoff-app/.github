<p align="center">
  <img src="https://www.forkoff.app/images/logo.png" alt="ForkOff" width="160"/>
</p>

<h1 align="center">ForkOff</h1>

<p align="center">
  <strong>Control Claude Code from your phone. Fork off from your desk — your code will be fine.</strong>
</p>

<p align="center">
  <a href="https://forkoff.app">forkoff.app</a> &bull;
  <a href="https://www.npmjs.com/package/forkoff">npm</a> &bull;
  <a href="https://forkoff.app/docs">Docs</a>
</p>

---

ForkOff connects [Claude Code](https://claude.ai/code) on your computer to your phone: real-time session monitoring, one-tap approvals for file edits and commands, usage analytics, and self-hosted Claude gateways — all end-to-end encrypted. Your code never touches our servers.

```bash
npm install -g forkoff
forkoff pair
```

## Repositories

| Repo | What it is |
|------|-----------|
| [forkoff-cli](https://github.com/Forkoff-app/forkoff-cli) | The `forkoff` CLI — pairs your machine with the mobile app and powers `forkoff remote` |
| [forkoff-backend](https://github.com/Forkoff-app/forkoff-backend) | Self-hostable backend: real-time relay, device pairing, and the Claude LLM gateway |
| [forkoff-react-native](https://github.com/Forkoff-app/forkoff-react-native) | The iOS/Android app (React Native + Expo) |

## Highlights

- **Mobile approvals** — review and approve Claude's file edits and commands from anywhere
- **Remote Claude accounts** — route any machine's Claude Code through your own server (`forkoff remote`)
- **End-to-end encrypted** — X25519 + XSalsa20-Poly1305; the relay only sees opaque blobs
- **Open source** — MIT licensed, self-hostable top to bottom
