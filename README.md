# linux-mint-pro-checklist
Linux Mint (XFCE) rendszerellenőrzési checklist és hibakeresési jegyzetek – személyes adatok nélkül.

# Linux Mint rendszerellenőrzés (publikus, privacy-safe)

Ez a repó egy **Linux Mint (XFCE) “pro” rendszerellenőrzési** jegyzet / checklist gyűjtemény.
Cél: gyorsan átlátni egy gép állapotát (hardver, tárhely, rendszer, audio, hálózat), és reprodukálható módon hibát keresni.

⚠️ **Adatvédelem / privacy**
- A repó **nem tartalmaz** nyers logokat, teljes parancskimeneteket, sorozatszámokat, hostnevet, felhasználónevet, IP-t, MAC-et, Wi-Fi SSID-t, fájlútvonalakat vagy bármilyen azonosítót.
- Csak **általánosítható módszertan**, parancsok és ellenőrzőpontok vannak benne.

## Tartalom
- `docs/checklist.md` – ellenőrzőlista (mit nézz meg először)
- `docs/commands.md` – “copy-paste” parancsgyűjtemény (safe módon)
- `docs/troubleshooting-playbook.md` – hibakeresési döntési fa (tünet → lépések)
- `docs/privacy-sanitization.md` – mit és hogyan kell anonimizálni
- `templates/` – sablonok issue-hoz és riporthoz

## Scope (mire fókuszál)
- Hardver alapszintű ellenőrzés (RAM/CPU/SSD-HDD)
- Tárhely és fájlrendszer (SMART, mount, jogosultságok)
- Hang (PipeWire / PulseAudio)
- Hálózat (DNS, alap connectivity)
- Naplózás és diagnosztika (journalctl) – **csak privacy-szűrt módon**

## Licenc
Ajánlott: MIT vagy CC BY 4.0 (amit szeretnél).
