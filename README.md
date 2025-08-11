# Cloud & Security RSS Feeds

This repository contains a curated list of **RSS feeds** for topics including:

- Cybersecurity & threat intelligence
- Cloud security (Microsoft Azure, Google Cloud Platform)
- DevSecOps
- Kubernetes, containers, and Docker security
- Identity & Access Management (IAM)
- Endpoint Detection & Response (EDR)

The feed list is stored in a `feeds.txt` file and is formatted for use with the [`ssddanbrown/rss`](https://github.com/ssddanbrown/rss) self-hosted RSS aggregator.

---

## 📄 What is `feeds.txt`?

This file follows the `ssddanbrown/rss` feed configuration format:

```
<feed-url> <friendly_name> [optional_color] [#tags]
```

Example:

```
https://krebsonsecurity.com/feed/ Krebs_on_Security #security #cyber
```

**Syntax rules:**
- One feed per line
- `#tags` help with filtering and grouping in the RSS app
- Colors can be added in square brackets after the name (CSS-compatible value)
- Lines starting with `#` are comments and ignored by the parser

---

## 🚀 How to Use

1. Install or deploy [`ssddanbrown/rss`](https://github.com/ssddanbrown/rss).
2. Clone this repository or download `feeds.txt`.
3. Place `feeds.txt` into your `rss` app’s config directory (see app docs for exact location).
4. Restart the RSS service.
5. The feeds will be automatically fetched and displayed.

---

## 📌 Why This List Exists

The goal is to maintain a **high-signal, low-noise** list of RSS feeds relevant to cloud and security professionals.  
Rather than manually visiting dozens of blogs, bulletins, and vendor update sites, this feed file provides a single place to get:
- Security advisories
- Cloud platform updates
- Threat intel
- Container/Kubernetes security news
- IAM & EDR developments

---

## 🤝 Contributing

Pull requests are welcome!  
If you have a feed to suggest, please:
1. Verify it is actively maintained (recent posts within the last 3–6 months).
2. Ensure it is relevant to **cybersecurity, cloud, DevSecOps, or IAM/EDR**.
3. Follow the formatting rules above.
4. Add appropriate `#tags`.

---

## 📜 License

This feed list is provided under the [MIT License](LICENSE).

---
