<h1 align="center">
  <br>
  <a href="https://play.google.com/store/apps/details?id=com.fancode.apps">
    <img src="https://github.com/hasanhabibmottakin/FC/blob/main/img/fancode_banner.png" alt="⭐ FanCode ⭐" width="220">
  </a>
  <br>
  ⭐ FanCode Live Fetcher ⭐
  <br>
</h1>

<p align="center">
  <b>Auto-updated FanCode HLS links • India & Bangladesh variants</b><br>
  Maintained by <strong>CoderBoyBD</strong> • Automated with <strong>GitHub Actions</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made_With-Python_3.12%2B-blue" alt="Python">
  <img src="https://img.shields.io/badge/Auto-Update_every_5_min-green" alt="Auto Update">
  <img src="https://img.shields.io/badge/Region-India%20%7C%20Bangladesh-orange" alt="Regions">
  <img src="https://img.shields.io/badge/License-Educational-yellow" alt="License">
</p>

---

## 📘 Overview
This repository automatically fetches and updates **FanCode live HLS (m3u8) stream links** in JSON and M3U formats using **GitHub Actions**.  
Both **India (in-mc-fdlive)** and **Bangladesh (bd-mc-fdlive)** variants are generated separately and kept updated automatically.

---

## 🔵 Key Features

- Auto-updates HLS links every 5 minutes  
- Supports India & Bangladesh variants  
- JSON format for developers  
- M3U playlist format for IPTV players  
- Handles live matches and premium streams  

---

## 🔗 Raw Data Links

| Type | Region | Raw Link |
|------|--------|----------|
| JSON | 🇮🇳 India | [in_rest_api.json](https://raw.githubusercontent.com/hasanhabibmottakin/fancode/main/in_rest_api.json) |
| JSON | 🇧🇩 Bangladesh | [bd_rest_api.json](https://raw.githubusercontent.com/hasanhabibmottakin/fancode/main/bd_rest_api.json) |
| M3U Playlist | 🇮🇳 India | [in_rest_playlist.m3u](https://raw.githubusercontent.com/hasanhabibmottakin/fancode/main/in_rest_playlist.m3u) |
| M3U Playlist | 🇧🇩 Bangladesh | [bd_rest_playlist.m3u](https://raw.githubusercontent.com/hasanhabibmottakin/fancode/main/bd_rest_playlist.m3u) |


---

## 🧾  Playlist Entry

```m3u
#EXTM3U
#EXTINF:-1 tvg-logo="https://www.fancode.com/skillup-uploads/cms-media/Bangladesh-vs-West-Indies-T20I_old-(1).jpg",West Indies Vs Bangladesh (West Indies tour of Bangladesh, 2025)
https://in-mc-fdlive.fancode.com/mumbai/137704_english_hls_e4a280240634404_1ta-di_h264/index.m3u8

