# Invoice Supplier (Masuk Invoice ke AutoCount)

Satu fail HTML yang membaca PDF invoice supplier dan menghasilkan senarai **nama supplier, no. invoice, tarikh**, untuk dimuat turun sebagai CSV atau disalin ke Excel.

- `index.html`: app ringkas. Buka terus dalam Chrome atau Edge, atau melalui GitHub Pages.

## Cara guna
1. Buka `index.html` dalam Chrome atau Edge (perlu internet untuk pembaca PDF, pdf.js dari cdnjs).
2. Seret PDF invoice ke kotak (boleh banyak).
3. Semak jadual, kemudian tekan **Muat turun CSV** atau **Salin untuk Excel**.

PDF dibaca dalam browser dan tidak dihantar ke mana-mana. Nama syarikat anda (penerima bil) boleh ditetapkan dalam kotak "Nama syarikat saya" supaya tidak dikira supplier.

## Had
- Hanya PDF yang ada teks (e-invoice biasa). PDF imbasan perlu diisi manual.
- Duplicate (supplier + no. invoice sama) tidak dieksport.
- Nama lajur CSV ialah susunan umum; padankan dengan template import AutoCount anda.
