# Bandy Golf — GitHub Pages

Game golf 3D satu lubang dengan avatar, kamera belakang bola, lima kayu golf dan kawalan kuasa / sasaran.

## Cara upload
1. Extract All fail ZIP ini di komputer.
2. Cipta repository GitHub baharu bernama golf-game.
3. Pilih Add file > Upload files (atau uploading an existing file untuk repository kosong).
4. Seret index.html, style.css, game.js, README.md dan folder vendor bersama-sama ke paparan upload.
5. Commit changes. Pastikan index.html berada terus pada halaman utama repository, bukan di dalam folder tambahan.
6. Buka Settings > Pages. Di Build and deployment, pilih Deploy from a branch, branch main dan folder / (root), kemudian Save.
7. Selepas deployment selesai, buka pautan yang dipaparkan di Settings > Pages.

Jangan upload ZIP sahaja: GitHub Pages memerlukan fail yang sudah diekstrak. Kekalkan folder vendor dan semua fail di dalamnya.

## Cara main
Pilih kayu > pilih gaya > laraskan kuasa dan sasaran > Pukul bola.
Anak panah kiri / kanan: sasaran. Space: pukul. R: pusingan baharu.
Driver, 5 Iron, 9 Iron, Wedge, Putter disediakan. Gaya: biasa, chip, pitch, flop.

## Keperluan dan batas
Pelayar perlu menyokong WebGL. Ini prototaip 3D, bukan grafik fotorealistik. Simulasi asas termasuk angin, graviti, lantunan, golekan, bunker, air dan skor.
Ujian simulasi telah lulus; visual WebGL tidak dapat diuji dalam pelayar ujian pembangunan.

## Lesen
Kod permainan dan model pemain asal dibina untuk projek Bandy. Enjin Three.js r160 menggunakan lesen MIT; lihat vendor/THREE-LICENSE.txt.
