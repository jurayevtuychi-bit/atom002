# Atom Fizikasi — Mobil Ilova (GitHub APK Build loyihasi)

Ushbu loyiha **Atom fizikasi** fanidan I–VIII modullarni qamrab olgan interaktiv mobil ilova bo'lib, **Capacitor** va **GitHub Actions** yordamida avtomatik ravishda Android `.apk` (`app-debug.apk`) formatiga o'tkazish uchun to'liq sozlangan.

## Ilova tarkibi
1. **Nazariy qism (I–VII Modullar, 15 ta mavzu):** Har bir mavzu 2600–3300 belgidan iborat ilmiy-akademik ma'ruza matni, interaktiv SVG sxemalar, tayanch formulalar hamda oflayn/onlayn video-animatsiyalar bilan boyitilgan.
2. **Virtual Laboratoriyalar (12 ta):**
   - 1. Plank doimiysini aniqlash (Virtual Lab & Simulyatsiya)
   - 2. Bote tajribasi (CURE konsepsiyasi)
   - 3. Fotoeffekt qonunlari (Scaffolding strategiyasi)
   - 4. Frank va Gers tajribasi (Inquiry-based Learning)
   - 5. Elektronning chiqish ishini aniqlash (CURE konsepsiyasi)
   - 6. Vodorodning Balmer seriyasidan to'lqin uzunligi (Virtual Lab & Simulyatsiya)
   - 7. Shtern va Gerlax tajribasi (Virtual Lab & Simulyatsiya)
   - 8. Rentgen nurlari spektri. Mozli qonuni (Inquiry-based Learning)
   - 9. Elektronning solishtirma zaryadi (Scaffolding strategiyasi)
   - 10. Elementar elektr zaryadi kattaligi (Inquiry-based Learning)
   - 11. Zeeman effekti (Scaffolding strategiyasi)
   - 12. Elektronlarning atom qobiqlari bo'yicha taqsimoti (Scaffolding strategiyasi)
3. **Mustaqil ta'lim (VIII Modul, 5 ta o'quv-tadqiqot loyihasi):** Nazariy sharh, 3 tadan amaliy topshiriq, bajarilish holati trekeri va o'z-o'zini tekshirish savollari.
4. **Amaliyot bo'limi:** Masalalar va yechimlar, Foton/Ridberg/Mozli kalkulyatori, 15 ta savollik Test (Quiz) va Interaktiv Krossvord.

## GitHub orqali APK yaratish qadamlari
1. GitHub'da yangi repozitoriy yarating.
2. Ushbu arxivdagi barcha fayllarni (`package.json`, `capacitor.config.json`, `www/index.html`, `.github/workflows/build-apk.yml`) repozitoriyga yuklang (`git push`).
3. GitHub sahifangizdagi **Actions** bo'limiga kiring — **Build Android APK** workflow avtomatik ishga tushadi.
4. 2–3 daqiqadan so'ng tayyor **`AtomFizikasi-debug-apk`** (`app-debug.apk`) faylini **Artifacts** bo'limidan yuklab oling!
