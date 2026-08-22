<div align="center">

# 📺 rzed — IPTV Indonesia Gratis · Playlist M3U & EPG XMLTV

## 📖 Cara Pakai

### 1. Install IPTV Player

| App | Platform | Catatan |
|-----|----------|---------|
| **TiviMate** | Android TV / Fire TV | ⭐ Paling recommended, support DASH/DRM |
| **OTT Navigator** | Android / Android TV | Support DASH/DRM + EPG bagus |
| **Kodi** + PVR IPTV Simple Client | Semua platform | Gratis, butuh add-on InputStream Adaptive untuk DASH/DRM |
| **VLC** | Semua platform | Universal, **tapi tidak support DRM** |
| **OttPlayer / SS IPTV** | Samsung / LG TV | Untuk Smart TV |
| **GSE Smart IPTV** | iOS / Apple TV | Untuk pengguna Apple |

### 2. Tambah Playlist

1. Buka player → **Add Playlist** / **Tambah Playlist**
2. Pilih **M3U URL**
3. Paste: `https://raw.githubusercontent.com/Rendzed/iptv/main/iptv.m3u`
4. Simpan, tunggu loading selesai.

EPG sudah tertanam di header playlist.

### 3. Channel "tidak didukung"?

Channel **(V+)** / **(DASH/MPD)** memakai format **DASH + DRM ClearKey**. Hanya jalan di player yang support DRM:
- ✅ **TiviMate**, **OTT Navigator** — native
- ✅ **Kodi** — install `InputStream Adaptive`
- ❌ **VLC / player bawaan Smart TV** — tidak support DRM → pakai playlist **OTT** atau channel grup **⚽ Bola Indonesia**

---

## 🗂️ Kategori Channel

### 🇮🇩 Indonesia

| Kategori | Contoh |
|----------|--------|
| **Nasional** | RCTI, SCTV, Trans TV, Trans 7, Indosiar, GTV, ANTV, Metro TV, MNCTV, TVRI, MDTV, MOJI |
| **Berita** | CNN Indonesia, CNBC Indonesia, iNews, tvOne, Kompas TV, BTV |
| **Olahraga / Bola** | TVRI, SCTV, MOJI, beIN Sports, SPOTV, Champions TV, Sportstars |
| **Regional** | Jawa Pos TV, JTV, Bali TV, Bandung TV, Jogja TV, Banjar TV, Sultra TV |
| **Hiburan** | HITS, CelebritiesTV, Vision Prime, Food Travel, Hanacaraka TV |

### 🌏 Internasional (27 negara)

🇺🇸 US · 🇬🇧 UK · 🇯🇵 Japan · 🇰🇷 Korea · 🇮🇳 India · 🇹🇷 Turkey · 🇹🇭 Thailand · 🇵🇭 Philippines · 🇻🇳 Vietnam · 🇲🇾 Malaysia · 🇸🇬 Singapore · 🇨🇳 China · 🇷🇺 Russia · 🇩🇪 Germany · 🇫🇷 France · 🇪🇸 Spain · 🇮🇹 Italy · 🇧🇷 Brazil · 🇲🇽 Mexico · 🇦🇷 Argentina · 🇨🇴 Colombia · 🇦🇪 UAE · 🇪🇬 Egypt · 🇸🇦 Saudi Arabia · 🇳🇬 Nigeria · 🇿🇦 South Africa · 🇵🇰 Pakistan

### ⚽🎬📰 Kategori Lain

| Kategori | Contoh |
|----------|--------|
| ⚽ **Sports** | beIN Sports 1-5, SPOTV, Sportstars 1-4, Premier Sports, TNT Sports, Fight Sports |
| 🎬 **Premium Movies** | HBO, HBO Hits, Cinemax, AXN, Galaxy, Studio Universal, Celestial Movies |
| 📰 **News** | CNN, BBC News, Al Jazeera, CNBC, Bloomberg, Euronews, France 24, DW |
| 👶 **Kids** | Nickelodeon, Nick Jr, Cartoon Network, DreamWorks, ZooMoo, CBeebies |
| 📚 **Documentary** | Discovery, National Geographic, BBC Earth, History, Animal Planet |
| 🎵 **Music & Radio** | MTV Live, MTV 90s, Music TV, Hard Rock FM, Prambors |

---

## 📡 EPG (Electronic Program Guide)

Jadwal acara dalam format **XMLTV** supaya muncul di TiviMate, Kodi, OTT Navigator, dan player lain. **Semua 1040+ channel punya entri EPG** (audit otomatis memastikan tidak ada yang bolong) dengan **25.000+ programme**; channel yang belum cocok dengan sumber EPG diberi placeholder *"Jadwal belum tersedia"* agar tetap terbaca player.

| Statistik | Nilai |
|-----------|-------|
| Channel dengan EPG | 650+ (100%) |
| Programme entries | 25.000+ |
| File size | ~9 MB |
| Format | XMLTV (`epg.xml`) |

**Sumber EPG:** epgshare01.online (Indonesia, Singapore, Malaysia, Canada, Italia, Prancis, UAE, India, Al Jazeera, **Polandia, Ceko**) · open-epg.com · AqFad2811/epg (Indonesia, Malaysia, Singapore, Brunei, Astro, Sooka, RTM, dll).

Channel tanpa jadwal asli tetap dibuatkan entry placeholder supaya terbaca semua IPTV player.

---
