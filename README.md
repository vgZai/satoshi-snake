# 🐍 Satoshi Snake ⚡

> **Stack Sats & Survive!**  
> Guide your node gently, stack Bitcoin blocks, and grab ❄️ Time-Lock Freeze and ⛏️ Mini-Halvings!

A cyberpunk Bitcoin arcade game built for the **Bitcoin Vibe Camp Olympics 2026** (Próspera, Roatán).

---

## 🎮 Play Live
- **GitHub Pages:** [https://vgzai.github.io/satoshi-snake/](https://vgzai.github.io/satoshi-snake/)
- **Bitcoin Vibe Camp Arcade:** [https://bitcoinvibe.camp/x/hackers/vitali/](https://bitcoinvibe.camp/x/hackers/vitali/)

---

## ⚡ Features

- **🎮 Retro Cyberpunk Gameplay:** Responsive HTML5 Canvas engine with smooth grid movement, input queue buffering, and sound synthesizer.
- **⚡ Bitcoin Lightning Zaps:**
  - 1-click 21-sat creator zaps via **WebLN** (`window.webln` / Alby).
  - Instant LNURL-pay invoice & dynamic QR code fallback for mobile and standard Lightning wallets.
- **🟣 Nostr Protocol Integration:**
  - **NIP-05 Verification:** Resolves verified handles (`vitali@bitcoinvibe.camp`) and Kind 0 profile metadata.
  - **NIP-07 Signer Login:** Connect with browser extensions (Alby, nos2x).
  - **Kind 30762 (Gamestr Event):** Broadcasts high scores directly to decentralized gaming leaderboards.
  - **Kind 1 (Social Note):** Share your score with hashtags to Nostr relays.
  - **NIP-57 (Zap Requests):** Supports signed Kind 9734 zap requests.
- **🏆 On-Chain Vibe:** Power-ups including ❄️ Time-Lock Freeze (difficulty slow-mo) and ⛏️ Mini-Halvings (+15 Sats bonus).

---

## 🛠️ Tech Stack
- **Frontend:** Vanilla JavaScript (ES6+), HTML5 Canvas, CSS3
- **Decentralized Protocol:** Nostr WebSocket Relays (NIP-01, NIP-05, NIP-07, NIP-57)
- **Payments:** Bitcoin Lightning Network (LNURL-pay, WebLN)
- **Audio:** Web Audio API Frequency Synthesizer

---

## 👤 Creator
- **GitHub:** [@vgZai](https://github.com/vgZai)
- **Nostr:** `vitali@bitcoinvibe.camp` (`npub1v42faa37mfmctvnv8ey7gkmna7f747g9jpa3h5zt2xx4z9clyggqypj0la`)
- **Lightning:** `innocent-worm-65@rizful.com`
