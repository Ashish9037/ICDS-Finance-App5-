# ICDS Finance Management System 💰

**Integrated Child Development Services - ફાઇનાન્સ મેનેજમેન્ટ સિસ્ટમ (Version 7)**

---

## 📱 APK ડાઉનલોડ કરો

1. GitHub પર **Actions** tab ખોલો
2. **Build Android APK** workflow ક્લિક કરો
3. છેલ્લો successful run ખોલો
4. **Artifacts** section માં **ICDS-Finance-App** ક્લિક કરીને APK download કરો

---

## 🚀 GitHub Actions — Auto APK Build

`main` branch પર code push કરો — GitHub automatically APK build કરશે.

### Steps:
```
1. GitHub પર new repository બનાવો
2. આ ફોલ્ડરની ફાઈલ upload કરો
3. Actions tab → Build Android APK → Run workflow
4. Build complete થાય ત્યારે Artifacts માંથી APK download કરો
```

---

## 🗂️ ફાઇલ સ્ટ્રક્ચર

```
ICDS-App/
├── www/
│   └── index.html          ← મુખ્ય Application
├── .github/
│   └── workflows/
│       └── build-apk.yml   ← APK Build Script
├── capacitor.config.json   ← App Configuration
├── package.json            ← Dependencies
├── .gitignore
└── README.md
```

---

## ⚙️ App ની માહિતી

| વિગત | મૂલ્ય |
|------|--------|
| App ID | com.icds.financemanagement |
| App Name | ICDS Finance |
| Version | 7.0.0 |
| Default Password | 1975 |
| Language | Gujarati (gu) |

---

## 🔒 ડેટા સ્ટોરેજ

- ડેટા **localStorage** માં save થાય છે
- Backup: JSON ફાઇલ download/upload
- PDF Export: Report & Summary

---

## 📞 Support

ICDS Finance Management System — Gujarat Government
