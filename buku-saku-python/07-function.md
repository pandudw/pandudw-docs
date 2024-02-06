# 07 Function

### Apa itu Function?

Ketika bikin kode program, kadang kita harus nulis kode yang jalanin tugas berulang ulang. Nah pengulangan ketika kita nulis kode yang jalanin tugas yang sama itu ga efektif.&#x20;

Trus gimana dong biar efektif ?! Function hadir untuk ngatasin masalah itu. Yuk, kita kenalan sama function.&#x20;

> A function is a block of code which only runs when it is called.

Jadi, function itu potongan kode yang dibuat dalam satu kumpulan kode (blok kode) biar bisa digunain berulang kali (_reusable_), ringkas, dan terstruktur.&#x20;

Masih belum ada gambaran? Perhatiin contohnya!

Pada beberapa kode program sebelumnya, kita bikin kode sederhana untuk perhitungan angka seperti ini.

```python
angka_1 = 10
angka_2 = 15

print(f"Hasil penjumlahan dari {angka_1} + {angka_2} adalah {angka_1 + angka_2}")

angka_3 = 11
angka_4 = 11
print(f"Hasil penjumlahan dari {angka_3} + {angka_4} adalah {angka_3 + angka_4}")

angka_5 = 17
angka_6 = 20
print(f"Hasil penjumlahan dari {angka_5} + {angka_6} adalah {angka_5 + angka_6}")
```

Kode di atas adalah contoh kode yang ga efisien karena mengulangi kode program yang sama. Bayangin, baru aja buat penjumlahan 3 kali, kalau perlu jumlahin 100 kali? belum lagi kalau ada pengurangan, perkalian, atau pembagian.

Sekarang, kita coba improve pakai function biar lebih efisien.

```python
def penjumlahan(angka_1, angka_2):
    print(f"Hasil penjumlahan dari {angka_1} + {angka_2} adalah {angka_1 + angka_2}")

penjumlahan(10, 15)
penjumlahan(11, 11)
penjumlahan(17, 20)
```

See? kita hanya perlu buat satu kode blok yang nantinya bisa dipanggil berulang kali dengan gampang.
