<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,100:4ECDC4&height=200&text=NontonAnimID-API&fontSize=50&fontColor=fff&animation=fadeIn&fontAlignY=40&desc=A%20RESTFul%20Anime%20Api&descAlignY=55&descSize=15"/>
</div>

<p align="center">
  <a href="https://nontonanimeid-api.vercel.app">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=F7F7F7&background=00000000&center=true&vCenter=true&multiline=true&width=550&height=100&lines=%F0%9F%9A%80+Welcome+to+NontonAnimeID+API;%E2%9C%A8+Restfull+Anime+%26+Comic+Api" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://nontonanimeid-api.vercel.app"><img src="https://img.shields.io/badge/REST-API-FF6B6B?style=for-the-badge&logo=fastapi&logoColor=white" /></a>
  <a href="#"><img src="https://img.shields.io/badge/100%25-FREE-00D9FF?style=for-the-badge" /></a>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Open-Source-4ECDC4?style=for-the-badge" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Uptime-99.9%25-brightgreen?style=for-the-badge" /></a>
</p>

---

<h2 align="center">
  🌟 The Most Comprehensive Anime API Platform
</h2>

<p align="center">
  <strong>Powering thousands of applications worldwide with real-time anime and comic data</strong>
</p>

---

## 🎯 Overview

**NontonAnimeID API** is a powerful, free REST API service that provides comprehensive access to anime and comic data. With coverage spanning from 1917 to the present day, our API offers developers a robust solution for building anime and comic-related applications.

### ✨ Key Highlights

- 📊 **50,000+** Anime titles in database
- 🚀 **<100ms** Average response time
- 🌍 **10M+** API calls served monthly
- 🔄 **Real-time** updates for new releases
- 🌐 **Multi-language** support (ID, JP)

---

## 🔗 Quick Start

### 🎬 Anime API

```
GET https://nontonanimeid-api.vercel.app
```

---

## 🚀 Features

#### Core Features
- ✅ **Complete Database** - 50,000+ anime titles
- ✅ **Episode Tracking** - Real-time episode updates
- ✅ **Streaming Links** - Multiple quality options
- ✅ **Advanced Search** - Title, genre, year, status
- ✅ **Seasonal Anime** - Current & upcoming seasons

#### Extended Features
- ✅ **Character Database** - 100,000+ characters
- ✅ **Voice Actors** - Complete seiyuu information
- ✅ **Reviews & Ratings** - Community ratings
- ✅ **Watch History** - Track user progress
- ✅ **Recommendations** - AI-powered suggestions

---

## 📡 API Sources

# 🎬 Anime Sources

| Platform | Description | URL |
|----------|-------------|-----|
| **NontonAnimeID** | Popular anime streaming source | [s8.nontonanimeid.boats](https://s8.nontonanimeid.boats) |

---

## 💻 API Usage Examples

### 🔧 Quick Integration

<details>
<summary><b>JavaScript / Node.js</b></summary>

```javascript
const getAnimeData = async () => {
  const response = await fetch('https://nontonanimeid-api.vercel.app/search/boruto/1');
  const data = await response.json();
  return data;
};
```

</details>

<details>
<summary><b>Python</b></summary>

```python
import requests

def search_anime(query, page):
    response = requests.get(f'https://nontonanimeid-api.vercel.app/search/{query}/{page}')
    return response.json()
```

</details>

<details>
<summary><b>PHP</b></summary>

```php
function getAnimeByGenre($genre, $page = 1) {
    $url = "https://nontonanimeid-api.vercel.app/genres/$genre/$page";
    $response = file_get_contents($url);
    return json_decode($response, true);
}
```

</details>

---

## 📊 API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/` | - | Get Root Dokumentasi |
| `/home` | GET | Get home anime list |
| `/top10` | GET | Get the 10 best anime right now |
| `/popular` | GET | Get popular anime list |
| `/schedule` | GET | Get airing schedule |
| `/anime/{slug}` | GET | Get anime details |
| `/completed/{page}` | GET | Get complete anime |
| `/ongoing` | GET | Get ongoing anime |
| `/genres` | GET | Get all genre list |
| `/genres/{genre}/{page}` | GET | Filter by genre |
| `/episode/{slug}` | GET | Get episode list |
| `/search/{query}/{page}` | GET | Search anime by query |

---

## 🎨 Popular Categories

### 🎬 Anime Genres

<p align="center">
  <img src="https://img.shields.io/badge/Action-FF6B6B?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Adventure-4ECDC4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Comedy-FFD93D?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Drama-6C63FF?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Fantasy-FF6BAD?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Horror-2D3436?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Isekai-00B894?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Magic-A29BFE?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Mecha-636E72?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Military-2D3436?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Music-FD79A8?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Mystery-6C5CE7?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Psychological-74B9FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Romance-FF6B9D?style=for-the-badge" />
  <img src="https://img.shields.io/badge/School-55A3FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Sci--Fi-00CEC9?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Shounen-FF7675?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Shoujo-FDCB6E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Slice_of_Life-81ECEC?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Sports-00B894?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Supernatural-A29BFE?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Thriller-2D3436?style=for-the-badge" />
</p>

---

### 📥 Download Quality Options

<p align="center">
  <img src="https://img.shields.io/badge/360p-Mobile-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/480p-SD-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/720p-HD-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/1080p-Full_HD-red?style=for-the-badge" />
</p>

---

## ⚡ Performance & Reliability

### 🚀 Speed
**<100ms**  
Average Response Time

### 📊 Scale
**10M+**  
Monthly API Calls

### 🛡️ Uptime
**99.9%**  
Service Availability

### 🔄 Updates
**Real-time**  
Content Refresh

---

## 🛠️ Built For Developers

### 🎯 Use Cases

#### 📱 Mobile Apps
Build iOS & Android apps with our comprehensive API

#### 🌐 Web Applications
Create responsive web apps with real-time data

#### 🤖 Discord Bots
Power your Discord server with anime/comic features

#### 📊 Data Analysis
Research and analyze anime/comic trends

#### 🎮 Game Development
Integrate anime/comic data into your games

#### 🔔 Tracking Apps
Build watchlist and reading list applications

---

## 📖 Documentation

### 🚧 Complete Documentation Coming Soon!

**What to expect:**
- 📝 Detailed endpoint specifications
- 🔐 Authentication & rate limiting guides
- 💡 Best practices & optimization tips
- 🛠️ SDK libraries for multiple languages
- 📚 Code examples & tutorials
- 🎯 Use case implementations

**Current Resources:**
- 📧 Email: support@fanime.biz.id
- 💬 Discord: Join our developer community
- 📱 WhatsApp: Quick support channel

---
---

## 🎬 FaNime - Streaming Platform

<div align="center">

### 🌟 Streaming Anime Terlengkap & Tanpa Iklan

<p align="center">
  <a href="https://www.fanime.biz.id/">
    <img src="https://img.shields.io/badge/🎬_WATCH_NOW-FANIME.BIZ.ID-FF6B6B?style=for-the-badge&logo=play&logoColor=white" />
  </a>
</p>

**🔗 Platform Streaming:** [fanime.biz.id](https://www.fanime.biz.id)

</div>

**Keunggulan Platform:**
- ✅ **Koleksi Terlengkap** - Ribuan anime dari berbagai genre
- ✅ **Tanpa Iklan** - Pengalaman menonton tanpa gangguan
- ✅ **Kualitas HD** - Streaming dengan kualitas terbaik
- ✅ **Update Cepat** - Episode terbaru langsung tersedia
- ✅ **Subtitle Indonesia** - Subtitle lengkap dan akurat
- ✅ **Multi Device** - Akses dari smartphone, tablet, atau PC

**Perfect for:**
- 🎯 Menonton anime favorit tanpa gangguan iklan
- 🎯 Streaming anime ongoing terbaru
- 🎯 Menikmati anime klasik dan populer
- 🎯 Binge-watching dengan kualitas terbaik

---

---

## 📱 Connect With Us

<div align="center">
  
### 🔔 Stay Updated with Latest API News & Features!

</div>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VaxYWls5q08hTLgqKp3K">
    <img src="https://img.shields.io/badge/WhatsApp_Channel-%2325D366.svg?style=for-the-badge&logo=whatsapp&logoColor=white" />
  </a>
</p>

<p align="center">
  <a href="https://www.instagram.com/fadzzzdigital_">
    <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white" />
  </a>
  <a href="https://t.me/cs_fadzzzdigital">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" />
  </a>
</p>

---


## 💝 Support This Project

### ⭐ Star This Repository
If you find NontonAnimeID API useful, please give it a star!

### 🚀 Contribute
We welcome contributions! Feel free to submit pull requests or report issues.

### ☕ Donate me
Support the development and server costs:

<p align="center">
  <a href="https://sociabuzz.com/fadzzzdigital/tribe">
    <img src="https://img.shields.io/badge/Donate-Support_Development-FF6B6B?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white" />
  </a>
</p>

---

## ⚠️ Terms of Service

### Fair Use Policy

- ✅ **Free for personal and commercial use**
- ✅ **No API key required for basic access**
- ⚠️ **Rate limit: 1000 requests/hour per IP**
- ⚠️ **Please cache responses when possible**
- ❌ **Do not abuse or overload the service**

### Copyright Notice

All anime and comic content metadata is sourced from publicly available information. We respect intellectual property rights and will promptly address any copyright concerns.

---

## 📜 License

<div align="center">
  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

</div>


---

<div align="center">
  <h2>🚀 Start Building Amazing Projects Today!</h2>
  
  <a href="https://www.fanime.biz.id">
    <img src="https://img.shields.io/badge/🌐_GET_STARTED-FANIMR.BIZ.ID-FF6B6B?style=for-the-badge&logo=google-chrome&logoColor=white" />
  </a>
  
  <br><br>
  
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=FF6B6B&center=true&vCenter=true&width=435&lines=Made+with+%E2%9D%A4%EF%B8%8F+by+Developers;For+Developers+Worldwide!+%F0%9F%8C%8D;Thank+you+for+visiting!+%F0%9F%99%8F" alt="Typing SVG" />
  
</div>

---

<footer align="center">
  <p><strong>© 2026 Fadzzz Digital</strong> • All Rights Reserved</p>
  <p>Crafted with passion by <a href="https://github.com/fadzzz404">@Fadzzz Digital</a></p>
  <br>
  <p>
    <img src="https://komarev.com/ghpvc/?username=fadzzz404&label=Profile%20Views&color=FF6B6B&style=for-the-badge" alt="Profile Views">
    <img src="https://img.shields.io/badge/API_Status-Online-brightgreen?style=for-the-badge" alt="API Status">
    <img src="https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge" alt="Version">
  </p>
</footer>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4ECDC4,100:FF6B6B&height=120&section=footer"/>
