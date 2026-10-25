# Al-Mussafir – Luxury Umrah Suite

A free, multilingual companion app for Umrah pilgrims. It runs in the browser, works offline after the first visit, and can be installed on a phone home screen.

## Features

- Prayer times for Makkah and Medina, with a next-prayer countdown
- Quran reader and Du'a collection
- Digital Dhikr counter
- Tawaf and Sa'i counter
- Qibla compass
- Places & Guide for Makkah and Medina, with search and maps (including your current location)
- Mosque gate finder and hotel tracker
- Currency converter
- Rawdah reservation guide
- Packing checklist and emergency information
- Sadaqah (links to official donation channels)
- 11 languages, including right-to-left Arabic and Urdu

## Files

| File | Purpose |
|---|---|
| `index.html` | The app (all code and content in one file) |
| `manifest.json` | App name, colours and icons for installing on a phone |
| `sw.js` | Service worker: stores the app so it opens without internet |
| `privacy.html` | Privacy policy |
| `icons/` | App icons |

## Run locally

Open `index.html` in a browser, or start a simple server from this folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Data and privacy

Settings and personal choices are saved on your device only. Live information (prayer times, weather, exchange rates, maps) is loaded from external services. Location is used only when you tap a button that needs it, and it is not stored. See [privacy.html](privacy.html) for details.

## Notes

- Live data requires an internet connection.
- The Islamic guides and duas are general guidance. Please verify them with a qualified scholar.
- Donation links currently point to [ehsan.sa](https://ehsan.sa).

## Contact

ibragimmagomedovich1233@gmail.com
