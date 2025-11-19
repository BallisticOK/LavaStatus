# LavaStatus Community Nodes
The most advanced, beautiful, and truly decentralized public Lavalink registry.

Live Site → https://your-domain.com
API Docs → https://your-domain.com/api
Health → https://your-domain.com/health
GitHub → https://github.com/YourUsername/lavalink-community

────────────────────────────────────────

How to Add Your Nodes (3 Minutes)

1. Fork this repository
2. Get your Discord User ID
   • Open Discord → Settings → Advanced → Enable Developer Mode
   • Right-click your profile → Copy ID
   Example: 1095331935787679795

3. Create your folder
   contributors/1095331935787679795/

4. Add info.json (your name + badge + avatar)
{
  "name": "DEDSEC",
  "badge": "Founder",
  "avatarHash": "a_9d8e8f9e8f9e8f9e8f9e8f9e8f9e8f9e"
}

5. Add nodes.json (your Lavalink nodes)
[
  {
    "identifier": "DEDSEC Node • Australia",
    "host": "58.172.0.148",
    "port": 2333,
    "password": "youshallnotpass",
    "secure": false,
    "restVersion": "v4"
  }
]

6. Commit → Push → Open Pull Request

Your nodes go live instantly when merged.

────────────────────────────────────────

Folder Structure
contributors/
├── 1095331935787679795/
│   ├── info.json
│   └── nodes.json
└── 727681845693104198/
    ├── info.json
    └── nodes.json

────────────────────────────────────────

Popular Badges
Founder • Top Host • Verified • Premium • Legend • Early Supporter
Just type whatever you want in "badge"

────────────────────────────────────────

Rules
• Public nodes only
• Real uptime >90%
• Correct secure: true/false
• Lavalink v3 or v4 only

Made with love by 0x00sec

Star • Fork • Add your nodes • Become immortal

https://github.com/YourUsername/lavalink-community
