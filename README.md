<h1 align="center">
  🏏 FanCode Live Matches API (Auto Updated)
</h1>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/en/5/53/Fancode_logo.png" width="180" alt="FanCode Logo">
</p>

<p align="center">
  <b>🇮🇳 India & 🇧🇩 Bangladesh Region Auto Updated APIs</b><br>
  Powered by <b>CoderBoyBD</b> • Maintained via GitHub Actions (every 5 mins)
</p>

---

### 📅 Last Updated
> **{{LAST_UPDATED}}**

---

### 📦 API Files

| File Name | Description | Region |
|------------|-------------|--------|
| [`in_rest_api.json`](./in_rest_api.json) | Main FanCode API data (with metadata & matches) | 🇮🇳 India |
| [`bd_rest_api.json`](./bd_rest_api.json) | Region-based API (mirrors IN → BD CDN) | 🇧🇩 Bangladesh |

---

### 🎵 Playlist Files (M3U Format)

| File Name | Description | Includes |
|------------|-------------|-----------|
| [`in_rest_playlist.m3u`](./in_rest_playlist.m3u) | Auto-generated playlist with **LIVE** / **STARTED** matches | Indian CDN |
| [`bd_rest_playlist.m3u`](./bd_rest_playlist.m3u) | Same playlist but using **Bangladesh CDN** (`bd-mc-fdlive`) | BD CDN |

---

### ⚙️ Update Mechanism

- ⏰ Runs every **5 minutes**
- 🧠 Fetches source from: `https://raw.githubusercontent.com/jitendra-unatti/fancode/refs/heads/main/data/fancode.json`
- 🧩 Updates metadata:
  - `Author` → `CoderBoyBD`
  - `User-Agent` → `CoderBoyBD/8.0.0 (Linux;Android/13) AndroidXMedia3/1.1.1`
- 🪄 Generates:
  - `in_rest_api.json`
  - `bd_rest_api.json`
  - `in_rest_playlist.m3u`
  - `bd_rest_playlist.m3u`
- 🚀 Auto pushes changes via GitHub Actions

---

### 🧠 Example Playlist Entry

```m3u
#EXTM3U
#EXTINF:-1 tvg-logo="https://www.fancode.com/skillup-uploads/cms-media/Bangladesh-vs-West-Indies-T20I_old-(1).jpg",West Indies Vs Bangladesh (West Indies tour of Bangladesh, 2025)
https://in-mc-fdlive.fancode.com/mumbai/137704_english_hls_e4a280240634404_1ta-di_h264/index.m3u8
