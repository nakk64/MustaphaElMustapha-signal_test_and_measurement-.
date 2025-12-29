# MustaphaElMustapha-signal_test_and_measurement-.
5G Measurement android app
# Signal Test & Measurement App

A mobile application for real-time LTE and 5G (NSA/SA) cell measurement, map visualization, and speed testing.  
Built with **Flutter** (UI + visualization) and **Kotlin** (native Android recorder).

---

## Features
- Detect LTE, 5G NSA, and 5G SA.
- Record KPIs: RSRP, RSRQ, SINR, PCI, EARFCN/NRARFCN.
- Color-coded map markers:  
  **Red** = Serving, **Green** = LTE, **Light Blue** = 5G NSA, **Dark Blue** = 5G SA.
- Live screen with current KPIs.
- Speed test: ping, download, upload.
- Local SQLite database for all cells.

---

## How to Use
1. Install the app on an Android device with LTE/5G support.  
2. Grant **Location** and **Phone** permissions.  
3. Start the recorder (foreground service).  
4. Use:
   - **Live Screen** → see current KPIs.  
   - **Map Screen** → view recorded cells on Google Maps.  
   - **Speed Screen** → run latency, download, and upload tests.  

---

## Notes
- Google Maps API key required.  
- Data is stored locally.  
- App is for **education and research** only.
