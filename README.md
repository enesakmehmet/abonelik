# Abonem — Gizlilik Politikası Sitesi

Tek sayfalık statik site (`index.html`). Bağımlılık yok, direkt GitHub Pages ile yayınlanabilir.

## GitHub'a yükleme

```bash
cd privacy
git init
git add .
git commit -m "Gizlilik politikası"
git branch -M main
git remote add origin https://github.com/<kullanici-adin>/<repo-adi>.git
git push -u origin main
```

## GitHub Pages'i aktif etme

1. GitHub'da repo → **Settings → Pages**
2. **Branch:** `main`, klasör: `/ (root)` seç → **Save**
3. Birkaç dakika sonra site şu adreste yayında olur:
   `https://<kullanici-adin>.github.io/<repo-adi>/`

Bu URL'yi App Store Connect'te **Privacy Policy URL** alanına yapıştır.
