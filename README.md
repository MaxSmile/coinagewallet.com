# coinagewallet.com — Coinage Wallet

**A fully client-side, open-source Web3 wallet focused on usability, security, and keyless onboarding.**  
Powered by Auth.js, Lit Protocol, and Ethers.js — all running on the frontend.

---

## 🌐 Live Demo

[https://coinagewallet.com](https://coinagewallet.com)

---

## 🚀 Features planned

- 🔐 **Keyless wallet** — users authenticate with Google, Apple, Email, etc. (via Auth.js)
- 🧠 **Private key stored with Lit Protocol** — access gated by a JWT
- 🧱 **Built with Ethers.js** — simple, powerful Ethereum integration
- 📦 **No database required** — all logic runs client-side
- ✅ **Secure and recoverable** — key access restored via social/email login

---

## 🔧 Tech Stack

| Layer           | Tool                                           |
|----------------|------------------------------------------------|
| Auth           | [Auth.js](https://authjs.dev/)                 |
| Key Management | [Lit Protocol](https://litprotocol.com/)       |
| Blockchain     | [Ethers.js](https://docs.ethers.org/)          |
| Hosting        | [Vercel](https://vercel.com/) or static hosting |

---

## 🛠️ How It Works

1. User **logs in** via Auth.js (Google, Apple, Email, etc.)
2. Auth.js issues a **JWT**
3. This JWT authorizes access to an **encrypted private key** via Lit Protocol
4. The key is **decrypted locally** in-browser
5. Wallet is now ready to **sign transactions with Ethers.js**

---

## ✨ Why Coinage Wallet?

- ✅ No seed phrases
- ✅ No MetaMask extensions
- ✅ No backend to attack
- ✅ Seamless access recovery via social/email login
- ✅ Mobile-friendly by design

---

## 📦 Getting Started

```bash
git clone https://github.com/yourname/coinagewallet.git
cd coinagewallet
yarn
yarn dev

## 📄 License

Licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).  
Attribution required — please retain credit to the original developer: **Vasilkoff Ltd (vasilkoff.com)**.

