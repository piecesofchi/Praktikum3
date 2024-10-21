# Praktikum3
## Menentukan Bilangan Terbesar

### Menentukan Bilangan Terbesar menggunakan Python
Untuk menentukan bilangan terbesar dengan menggunakan Python, Kita bisa menggunakan fungsi max() atau dengan melakukan iterasi secara manual '<p>'
Menggunakan max()

Daftar bilangan
bilangan = [10, 20, 5, 40, 30]

Menentukan bilangan terbesar
bilangan_terbesar = max(bilangan)

print("Bilangan terbesar adalah:", bilangan_terbesar)

Menggunakan Iterasi

Daftar bilangan
bilangan = [10, 20, 5, 40, 30]

Inisialisasi bilangan terbesar dengan nilai pertama dalam daftar
bilangan_terbesar = bilangan[0]

Iterasi untuk mencari bilangan terbesar
for num in bilangan:
    if num > bilangan_terbesar:
        bilangan_terbesar = num

print("Bilangan terbesar adalah:", bilangan_terbesar)

Flowchart
![img]screenshot/ss2.jpeg