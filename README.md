# LavaStatus Community Monitor
The most advanced, beautiful, and truly decentralized public Lavalink registry.

This monitor aggregates nodes from local files, public lists, and the **BallisticOK/LavaStatus** community repository.

Live Site → https://your-domain.com
API Docs → https://your-domain.com/api
Health → https://your-domain.com/health
Source Code → https://github.com/YourUsername/lavalink-community

────────────────────────────────────────

## 🤝 How to Add Your Nodes to the Community
Your nodes will be automatically added to *this* monitor if they are accepted into the official community list.

**The nodes are fetched from:** **[BallisticOK/LavaStatus/contributors](https://github.com/BallisticOK/LavaStatus)**

To contribute:

1.  **Fork the Community Repository:**
    Go to **[BallisticOK/LavaStatus](https://github.com/BallisticOK/LavaStatus)** and fork the project.

2.  **Get your Discord User ID:**
    * Open Discord → Settings → Advanced → Enable Developer Mode
    * Right-click your profile → Copy ID
    * *Example: 1095331935787679795*

3.  **Create your folder:**
    `contributors/YOUR_USER_ID/`

4.  **Add `nodes.json`** (Your Lavalink nodes)
    ```json
    [
      {
        "identifier": "what you call your node",
        "host": "your host ip/hostname",
        "port": your port,
        "password": "yousexypassword",
        "secure": false,
        "restVersion": "v4"
      }
    ]
    ```

5.  **Commit, Push, and Open a Pull Request** in the **BallisticOK/LavaStatus** repository.

Your nodes go live across all monitors using this system when merged.

────────────────────────────────────────

## ⚙️ Deployment & Node Sources

This monitor fetches nodes from three sources:

| Source Type | Configuration File/Location | Description |
| :--- | :--- | :--- |
| **Local** | `nodes.json` (root directory) | Highest priority. For personal/private nodes. |
| **Public CDN** | Hardcoded in `index.js` | Public, well-known node lists (e.g., cdn.ballisticok.xyz). |
| **GitHub Community** | Hardcoded in `index.js` | Nodes from **BallisticOK/LavaStatus/contributors** are dynamically scanned and merged. |

### Folder Structure (Community Repo)
```

contributors/
├── 1095331935787679795/
│   └── nodes.json

```

────────────────────────────────────────

## 📝 Rules for Contribution
* Public nodes only.
* Real uptime >90% (monitored).
* Correct `secure: true/false` status.
* Lavalink v3 or v4 only.

Made with love by 0x00sec

**Star • Fork • Add your nodes • Become immortal**

**[https://github.com/BallisticOK/LavaStatus](https://github.com/BallisticOK/LavaStatus)**
```
