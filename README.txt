# Lula & Mom — Postpartum Reset

Aplikasi web statis/PWA sederhana untuk tracker harian postpartum, pumping, DBF, meal plan 30 hari, progress, dan shopping checklist.

## Cara deploy ke Vercel (gratis untuk penggunaan pribadi)
1. Ekstrak ZIP ini.
2. Buka https://vercel.com dan login / buat akun.
3. Buat repository GitHub baru, misalnya `lula-mom-reset`, lalu upload semua file dalam folder ini ke root repository.
4. Di Vercel pilih **Add New → Project**, import repository tersebut.
5. Framework preset: **Other**. Build command dan output directory biarkan kosong/default; tidak perlu build.
6. Klik **Deploy**. Vercel akan memberikan URL publik `*.vercel.app`.
7. Buka URL itu di Safari iPhone → tombol Share → **Add to Home Screen**.

## Data & privasi
- Catatan disimpan di localStorage browser pada perangkat yang digunakan.
- Data tidak otomatis tersinkron ke iCloud atau perangkat lain.
- Jangan clear website data/cache jika ingin mempertahankan catatan.
- Gunakan tombol Export CSV di tab Progress untuk backup.
- Jika membuka aplikasi di perangkat/browser berbeda, datanya tidak ikut pindah.

## Catatan
Meal plan adalah inspirasi menu, bukan preskripsi kalori. Karena supply ASI sedang menurun, jangan melakukan defisit agresif. Pastikan asupan bayi dan pertumbuhan dipantau; konsultasikan bila ada tanda asupan ASI tidak cukup.


## Fitur versi terbaru
- Calorie & food tracker: input nama makanan, gramasi, dan kcal per 100 g; kalori dihitung otomatis.
- Meal plan 30 hari dengan panduan gramasi awal untuk breakfast, lunch, dinner, dan snack.
- Calorie values are estimates; do not use as a restrictive target while milk supply is falling.
