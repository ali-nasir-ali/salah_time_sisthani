# salah_time_sisthani
simple html webapp where it fetches data from website and give daily namaz times

# 📲 Installing the Web App (PWA) on Your Android Phone

Once your GitHub Pages site is live, you can **install it on your Android phone** just like a regular app.

---

## 1. Open Chrome on Your Android Phone
- Launch the **Google Chrome** browser on your device.

---

## 2. Navigate to Your Web App
- Enter your GitHub Pages URL in the address bar:  


- Press **Enter** to load the page.

---

## 3. Install the App
There are two possible ways to install:

- **Automatic Prompt**:  
Chrome may show a banner at the bottom saying:  
*“Add Glasgow Prayer Times to Home screen”* → Tap it.

- **Manual Method**:  
1. Tap the **three-dot menu** (⋮) in the top-right corner.  
2. Select **Add to Home screen** or **Install app**.  
3. Confirm when prompted.

---

## 4. Confirm Installation
- Tap **Add** or **Install** in the confirmation dialog.

---

## 5. Check Your Home Screen
- The app icon will now appear on your **Home screen** or **App Drawer**.  
- When opened, it runs in a **standalone window** (without the browser bar), giving it a **native app feel**.

---

## ⚠️ Important Considerations

- **CORS Proxy Reliability**  
- Public CORS proxies can be unstable. If your app fails to fetch data, this is the first thing to check.  
- For long-term stability, consider hosting your own proxy (e.g., with **Node.js** or **Python** on a free cloud tier).

- **Website Structure Changes**  
- If [Najaf.org](https://www.najaf.org/english/prayer/glasgow) changes its HTML (e.g., class names), your parsing in `index.html` will break.  
- Update the parsing logic and push changes to GitHub if this happens.

- **Offline Support**  
- The `service-worker.js` enables basic offline access by caching core files.  
- You can reopen the app without internet, though prayer times won’t refresh.

- **No Push Notifications or Background Sync**  
- This simple PWA does **not** include advanced features like push notifications or background sync.  
- These would require additional JavaScript and server-side support.

---
