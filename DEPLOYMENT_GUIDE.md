# 🚀 THE-इन्सानियत PVT.LTD — Free Zero-Cost Deployment Guide

इस गाइड का उपयोग करके आप बिना ₹1 खर्च किए ऐप को पूरी दुनिया में डाउनलोड के लिए उपलब्ध करा सकते हैं:

---

## 📦 1. GitHub Actions से ऑटोमेटेड APK बिल्ड और रिलीज़ (Zero-Cost CI/CD)

हमने आपके लिए `.github/workflows/build-release.yml` सेटअप कर दिया है।

### कैसे इस्तेमाल करें:
1. अपने प्रोजेक्ट को GitHub पर पुश करें।
2. GitHub रिपॉजिटरी में **Actions** टैब पर जाएं।
3. **"Build & Release Android APK (Zero Cost)"** वर्कफ़्लो पर क्लिक करें और **"Run workflow"** दबाएं।
4. GitHub आपके लिए फ्री में क्लाउड पर APK कंपाइल करेगा और **Releases** में डाउनलोड के लिए अपलोड कर देगा!
5. आपको एक परमानेंट डाउनलोड लिंक मिल जाएगा जैसे:
   `https://github.com/<YOUR_USERNAME>/<YOUR_REPO>/releases/latest/download/app-debug.apk`

---

## 🌐 2. 100% फ्री डाउनलोडिंग वेबसाइट (GitHub Pages / Vercel / Netlify)

हमने एक रिस्पॉन्सिव लैंडिंग पेज `index.html` तैयार कर दिया है।

### GitHub Pages पर लाइव करने का तरीका:
1. अपनी GitHub रिपॉजिटरी की **Settings** > **Pages** में जाएं।
2. **Source** में `Deploy from a branch` चुनें और `main` ब्रांच (Root `/`) सेलेक्ट करके **Save** कर दें।
3. 2 मिनट में आपकी फ्री वेबसाइट लाइव हो जाएगी:
   👉 `https://<YOUR_USERNAME>.github.io/<YOUR_REPO>/`

### Vercel / Netlify पर लाइव करने का तरीका (1 Click):
1. [vercel.com](https://vercel.com) या [netlify.com](https://netlify.com) पर जाएं।
2. अपनी GitHub रिपॉजिटरी चुनें और **Deploy** पर क्लिक करें। आपकी वेबसाइट तुरंत लाइव हो जाएगी।

---

## 📲 3. WhatsApp & Social Media पर शेयर करने का तरीका
1. अपने APK को Google Drive या GitHub Releases पर अपलोड करें।
2. अपने लैंडिंग पेज (`index.html`) के `href="./app-release.apk"` में अपना डाउनलोड लिंक डाल दें।
3. अब अपने ग्राहकों और दोस्तों को लैंडिंग पेज का लिंक भेजें, जहाँ से वे एक क्लिक में ऐप डाउनलोड कर सकेंगे!
