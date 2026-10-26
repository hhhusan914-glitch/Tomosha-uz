TOMOSHA — ANDROID APK LOYIHASI (TELEFON ORQALI BUILD)

Funksiyalar:
- Android WebView ichida Tomosha HTML interfeysi.
- Anime qo‘shish: nomi, janrlari, yili, qismlar soni, tavsifi va 1-qism video URL.
- Katalogdagi qidiruv, janr filtrlari va saralash.
- Sevimlilar, ko‘rish tarixi, baholash va profil sozlamalari.
- Qo‘shilgan anime va kiritilgan video havolalari shu telefonning localStorage xotirasida saqlanadi.
- Video internetdan oqimli ijro qilinadi; to‘liq video faylni APK ichiga qo‘shish shart emas.

MUHIM CHEKLOVLAR:
- Bu versiyada umumiy server/backend yo‘q. Telefoningizga qo‘shgan anime va sevimlilar boshqa foydalanuvchilarga avtomatik ko‘rinmaydi; ilova ma’lumotlari shu qurilmada qoladi.
- Video URL to‘g‘ridan-to‘g‘ri video faylga olib borishi kerak (odatda HTTPS MP4 yoki WebM). Oddiy YouTube/watch sahifa URLsi HTML5 video oynasida to‘g‘ridan-to‘g‘ri ishlamaydi.
- Video havolasi ommaviy ochiladigan, login talab qilmaydigan bo‘lishi kerak. Hosting CORS yoki hotlink cheklovlari qo‘ygan bo‘lsa, ijro ishlamasligi mumkin.
- Faqat o‘zingiz joylagan yoki tarqatish huquqiga ega videolardan foydalaning.
- Bu loyiha APK build qilish uchun tayyorlangan; APKning o‘zi hali yig‘ilmagan.

APKNI FAQAT ANDROID TELEFONDA YIG‘ISH (GitHub Actions):
1. ZIPni yuklab oling va arxivdan chiqaring.
2. github.com saytida akkauntga kiring va yangi repository yarating (masalan, tomosha-android).
3. Repository ichida Add file -> Upload files ni bosing.
4. ZIPdan chiqqan TomoshaAndroid papkasining ICHIDAGI barcha fayl va papkalarni yuklang. .github papkasini ham qo‘shing; ZIPni o‘zini repositoryga tashlamang.
5. Commit changes ni bosing.
6. Actions bo‘limida “Build Tomosha APK” workflowini oching. Kerak bo‘lsa Run workflow ni bosing.
7. Build muvaffaqiyatli (yashil) bo‘lgach, ishga tushgan workflow sahifasidagi Artifacts qismidan “Tomosha-debug-APK” ni yuklab oling.
8. Artifact ZIPni chiqaring va app-debug.apk faylini oching. Android so‘rasa, brauzer yoki fayl menejeriga noma’lum ilovalarni o‘rnatish ruxsatini bering.

Agar Actions build xato bersa, xato logining oxirgi 20–40 qatorini yuboring.
