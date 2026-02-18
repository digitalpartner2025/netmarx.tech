# netmarx.tech
AI braingame – autonoomne mängu arhitekt
# Netmarx.tech – Autonoomne Mängu Arhitekt

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Netmarx.tech** on AI-põhine süsteem, mis toimib isemõtleva arhitekti, disaineri ja insenerina. See skaneerib sinu arvutis olevaid faile (nt allalaadimised, töölaud, dokumendid) ja kasutab kohalikku AI-d (Ollama), et nende põhjal genereerida uut koodi, ideid ja lahendusi – kõike eesmärgiga luua kaardimäng, mis on inspireeritud Heartstonest, kuid keskendub AI-turniiridele ja koodivõistlustele.

Süsteem on loodud töötama iseseisvalt: käivitad ühe käsu ja ta hakkab pidevalt õppima, looma ja täiustama, andes sulle terminalis reaalajas ülevaate oma tegevusest.

## ✨ Võimalused

- **Ohutu skaneerimine** – loeb tekstifaile (.py, .txt, .json, .md jne) sinu `Downloads`, `Desktop`, `Documents` ja `netmarx.tech` kaustadest, kuid ei muuda kunagi originaale.
- **AI-põhine looming** – kasutab kohalikku mudelit (nt Qwen2.5-Coder 30B) uute koodijuppide, klasside ja funktsioonide genereerimiseks.
- **Pidev õppimine** – kui tuvastab uusi faile, küsib AI-lt, mida nendega peale hakata ja loob vastava koodi.
- **GitHubi integratsioon** – otsib regulaarselt GitHubist inspiratsiooni (nt populaarseid kaardimängu projekte) ja salvestab tulemused.
- **Täielik läbipaistvus** – kõik tegevused logitakse nii terminali kui faili (`logs/creative_architect.log`).

## 🚀 Kiirestart

### Eeldused

- **macOS** (kood on testitud MacBookis)
- **Python 3.9+**
- **Ollama** – kohalik AI-mudelite haldur
  ```bash
  brew install ollama
  ollama pull qwen3-coder:30b   # või mõni väiksem mudel
