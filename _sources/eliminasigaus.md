---
title: eliminasigaus

---

# Metode Eliminasi Gauss

Metode Eliminasi Gauss digunakan untuk menyelesaikan sistem persamaan linear dengan mengubah matriks koefisien menjadi bentuk eselon baris melalui operasi baris elementer. Bentuk eselon baris ini memudahkan kita dalam menyelesaikan variabel satu per satu (substitusi mundur).

Berikut adalah langkah-langkah menyelesaikan sistem persamaan linear menggunakan metode eliminasi Gauss, serta menampilkan solusinya secara grafis menggunakan GeoGebra


**Sistem Persamaan Linear yang Digunakan**

x + y + z = 6

2x + 3y + z = 14

x − y + 2z = 8

Matriksnya, yaitu:

1  1  1 

2  3  1 

1 -1  2 


**Eliminasi Gauss (Operasi Baris)**

**Langkah 1: NOL-kan Elemen di bawah Elemen Pivot Pertama**

Pivot pertama sudah 1 di posisi (1,1). Kita buat elemen di bawahnya menjadi nol:

R₂ → R₂ - 2R₁
 
R₃ → R₃ - R₁

Hasilnya:

1  1  1 

0  1 -1 

0 -2  1 

**Langkah 2: NOL-kan Elemen di bawah Pivot Kedua**

Pivot kedua adalah 1 di posisi (2,2). Kita buat elemen di bawahnya menjadi nol:

R₃ → R₃ + 2R₂

Hasilnya:

1  1  1 

0  1 -1 

0  0 -1 

**Langkah 3: Buat Pivot Ketiga Menjadi 1**

Kita buat pivot ketiga menjadi 1:

R₃ → -R₃

Hasilnya:

1  1  1 

0  1 -1 

0  0  1 

**Back Substitution (Substitusi Mundur)**

Dari baris ketiga:

z = −6

Dari baris kedua:

y − (−6) = 2 ⇒ y + 6 = 2 ⇒ y = −4

Dari baris pertama:

x + (−4) + (−6) = 6 ⇒ x − 4 − 6 = 6 ⇒ x = 16

Jadi, solusinya adalah:

x = 16, y = −4, z = −6

<iframe src="https://www.geogebra.org/classic/awrbqz32?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>