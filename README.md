# wifi-qr-generator

📶 **Branded WiFi QR Generator**

**The Problem:** Sharing network credentials is a manual, friction-filled process. **The Solution:** A specialized serialization tool that converts raw WiFi metadata into the MECARD/WIFI protocol.

**Technical Highlights:**

**Protocol Handling:** Uses segno.helpers to ensure the generated strings meet the specific URI requirements for mobile camera recognition.

**Image Manipulation:** Leverages Pillow (PIL) to dynamically create a high-resolution canvas, injecting custom branding and typography onto raw QR data.

**Secure Session State:** Designed as a "Local-First" application to prevent sensitive credentials from being hardcoded or leaked to version control.

🛠️ **Tech Stack**

**Languages:** Python 3.x

**Frameworks:** Streamlit (UI), Pandas (Data Analysis)

**Libraries:** Segno (QR logic), Pillow (Image processing), Matplotlib (Visualization)
