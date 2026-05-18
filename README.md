# Rangkaian 7 Logic Gate — Praktikum Tinkercad

> Proyek ini merupakan hasil eksplorasi 7 gerbang logika menggunakan platform simulasi **Tinkercad Circuits**.

🔗 **Link Tinkercad: (https://www.tinkercad.com/things/kEKnP0JXo6c-powerful-kasi?sharecode=lxv0o_qQVZoQKBzp8AwTjg4a2ZMwKZkND34xMsRuhQk)


## Daftar Isi
- [Deskripsi]
- [Komponen yang Digunakan]
- [Penjelasan 7 Logic Gate]
- [Dokumentasi Rangkaian]
- [Tabel Kebenaran]
- [Anggota Kelompok]

---

## Deskripsi

Gerbang logika (logic gate) adalah komponen dasar dalam sistem digital yang bekerja berdasarkan aljabar Boolean. Setiap gerbang menerima satu atau lebih sinyal input biner (0 atau 1) dan menghasilkan satu sinyal output. Dalam praktikum ini, kami mensimulasikan 7 jenis gerbang logika menggunakan IC seri 74HC pada platform Tinkercad Circuits.

---

## 🔧 Komponen yang Digunakan

| Komponen | Keterangan |
|----------|------------|
| IC 74HC08 | AND Gate (4 gerbang 2-input) |
| IC 74HC04 | NOT Gate (6 gerbang 1-input) |
| IC 74HC00 | NAND Gate (4 gerbang 2-input) |
| IC 74HC32 | OR Gate (4 gerbang 2-input) |
| IC 74HC02 | NOR Gate (4 gerbang 2-input) |
| IC 74HC86 | XOR Gate (4 gerbang 2-input) |
| IC 74HC66 | XNOR Gate |
| DIP Switch | Input sinyal biner (0/1) |
| LED + Resistor | Indikator output |
| 9V Battery | Sumber tegangan |

---

## Penjelasan 7 Logic Gate

### 1. AND Gate (IC 74HC08)
Gerbang AND menghasilkan output HIGH (1) **hanya jika semua input bernilai HIGH (1)**. Jika salah satu atau semua input bernilai LOW (0), output akan LOW (0).

**Persamaan Boolean:** `Y = A · B`

---

### 2. NOT Gate / Inverter (IC 74HC04)
Gerbang NOT adalah gerbang dengan satu input yang **membalik (menginversi)** nilai inputnya. Input HIGH menghasilkan output LOW, dan sebaliknya.

**Persamaan Boolean:** `Y = Ā`

---

### 3. NAND Gate (IC 74HC00)
Gerbang NAND adalah kebalikan dari AND. Outputnya bernilai LOW (0) **hanya jika semua input HIGH**. Pada kondisi lain, output selalu HIGH.

**Persamaan Boolean:** `Y = A̅·̅B̅`

---

### 4. OR Gate (IC 74HC32)
Gerbang OR menghasilkan output HIGH (1) jika **minimal satu input bernilai HIGH**. Output hanya LOW jika semua input LOW.

**Persamaan Boolean:** `Y = A + B`

---

### 5. NOR Gate (IC 74HC02)
Gerbang NOR adalah kebalikan dari OR. Outputnya HIGH **hanya jika semua input LOW**. Jika ada satu input saja yang HIGH, output menjadi LOW.

**Persamaan Boolean:** `Y = A̅+̅B̅`

---

### 6. XOR Gate / Exclusive OR (IC 74HC86)
Gerbang XOR menghasilkan output HIGH jika **jumlah input HIGH adalah ganjil** (berbeda). Jika kedua input sama (keduanya 0 atau keduanya 1), output LOW.

**Persamaan Boolean:** `Y = A ⊕ B`

---

### 7. XNOR Gate / Exclusive NOR (IC 74HC66)
Gerbang XNOR adalah kebalikan dari XOR. Output HIGH jika **kedua input bernilai sama** (keduanya 0 atau keduanya 1).

**Persamaan Boolean:** `Y = A̅⊕̅B̅`

---

## 📸 Dokumentasi Rangkaian

### Tampilan Keseluruhan Rangkaian di Tinkercad

![Rangkaian 7 Logic Gate] 

> 


## Tabel Kebenaran

### AND Gate
| A | B | Y (A·B) |
|---|---|---------|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

### NOT Gate
| A | Y (Ā) |
|---|-------|
| 0 | 1 |
| 1 | 0 |

### NAND Gate
| A | B | Y (A̅·̅B̅) |
|---|---|----------|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

### OR Gate
| A | B | Y (A+B) |
|---|---|---------|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

### NOR Gate
| A | B | Y (A̅+̅B̅) |
|---|---|----------|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 0 |

### XOR Gate
| A | B | Y (A⊕B) |
|---|---|---------|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

### XNOR Gate
| A | B | Y (A̅⊕̅B̅) |
|---|---|----------|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

---

## 👥 Anggota Kelompok

| No | Nama |
|----|------|-----|-------------------|
| 1 | Reyza Ramadhan 
| 2 | Yona Okadino Saputra
| 3 | De' riffa Aditya Nugroho
| 4 | Erny Ginuny 

