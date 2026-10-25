# Add-ItemScan

Barcode scanning and real-time inventory synchronization with Google Sheets Web App.

---

## 🚀 Tungkol sa Proyekto
Ang **Add-ItemScan** ay isang Android application na idinisenyo upang mapabilis ang pag-scan ng barcode at pamamahala ng imbentaryo. Direktang nakakonekta ito sa Google Sheets gamit ang Google Apps Script (Web App) para sa real-time na pag-update at pag-save ng mga transaksyon tulad ng **New Items**, **Stock Out**, at **Receiving / Restocking**.

---

## ✨ Mga Pangunahing Tampok (Key Features)
* **Barcode Scanning:** Mabilis na pagbasa ng mga produkto gamit ang camera ng smartphone.
* **Main Item List (New Item Creation):** Awtomatikong pagdaragdag at pag-save ng bagong produkto sa Google Sheets.
* **Stock Out Recording:** Maayos na pagre-record ng mga lumalabas o nabentang item mula sa imbentaryo.
* **Receiving & Restock Tracking:** Real-time na pagdaragdag ng stock para sa mga bagong dating na delivery o paninda.
* **In-App Update System:** Direktang nag-a-update at nag-a-download ng bagong APK version mula sa Google Sheet web app nang hindi na lumilipat sa web browser.

---

## 🛠️ Tech Stack
* **Frontend:** Android (Kotlin / XML)
* **Backend / Database:** Google Sheets & Google Apps Script (JavaScript)
* **Integration:** Google Apps Script Web App Deployment (GET & POST Requests)

---

## 📂 Google Apps Script (`Code.gs`) Setup
Para kumonekta ang app sa iyong Google Sheets, i-deploy ang kasamang Google Apps Script bilang **Web App** na may mga sumusunod na kinakailangang tab:
1. `Inventory` (o `Master Items`) - Listahan ng mga produkto.
2. `Update` / `Update New` - Para sa App Version checking at APK downloading.

---

## 📄 License
Ang proyektong ito ay bukas para sa personal at komersyal na paggamit. Huwag kalimutang i-star ang repository kung nakatulong ito sa iyo!
