# Script Server

A lightweight shell script hosting repository powered by GitHub Pages.

Fetch, preview, and execute scripts directly from your terminal.

---

## 🌐 Base URL

```bash
ss.manish.kr
```

---

## 🚀 Quick Usage

Run any script directly:

```bash
curl -s ss.manish.kr/<script>.sh | bash
```

Example:

```bash
curl -s ss.manish.kr/alias.sh | bash
```

---

## 📜 Preview a Script Before Running

```bash
curl ss.manish.kr/alias.sh
```

---

## 📂 Available Scripts

| Script | Description |
|--------|-------------|
| `alias.sh` | Adds useful aliases to `.bashrc` |

---

## ⬇️ Download Without Executing

```bash
curl -O ss.manish.kr/alias.sh
```

or

```bash
wget ss.manish.kr/alias.sh
```

---

## 🛠 How It Works

- Scripts are stored in this GitHub repository
- Hosted using GitHub Pages
- Served through the custom domain `ss.manish.kr`
- Accessible publicly for quick terminal usage

---

## ⚠️ Security Notice

Always inspect scripts before executing them:

```bash
curl ss.manish.kr/alias.sh
```

Then run:

```bash
curl -s ss.manish.kr/alias.sh | bash
```

---

## 🤝 Contributing

Pull requests for useful scripts and improvements are welcome.

---

## 📄 License

GNU GENERAL PUBLIC LICENSE