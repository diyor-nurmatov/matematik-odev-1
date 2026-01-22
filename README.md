
---

# 📘 İkinci Dereceden Denklem Çözme Programı (C++)

## 🎓 Öğrenci Bilgileri

* **Öğrenci Numarası:** 2507020024
* **Ad Soyad:** Diyorbek Nurmatov
* **Ödev:** Ödev-1
* **Fakülte:** Bilgisayar Mühendisliği

---

Bu proje, C++ programlama dili kullanılarak yazılmış basit bir konsol uygulamasıdır. Program, kullanıcıdan alınan **a**, **b** ve **c** katsayılarına göre ikinci dereceden bir denklemin köklerini hesaplar.

Genel denklem formu:

[
ax^2 + bx + c = 0
]

Diskriminant formülü:

[
\Delta = b^2 - 4ac
]

Diskriminant değerine göre denklemin kökleri belirlenir.

---

## 🚀 Özellikler

* Kullanıcıdan `a`, `b`, `c` katsayılarını alır.
* Diskriminantı hesaplar.
* Diskriminanta göre:

  * Gerçek kök yoksa uyarı verir.
  * Tek gerçek kök varsa sonucu gösterir.
  * İki farklı gerçek kök varsa her ikisini gösterir.
* Basit ve anlaşılır konsol çıktısı sunar.

---

## 🛠️ Kullanılan Teknolojiler

* **Dil:** C++
* **Kütüphaneler:**

  * `<iostream>` → Giriş / çıkış işlemleri için
  * `<cmath>` → Matematiksel işlemler (karekök) için

---

## 📂 Dosya Yapısı

```
📁 Proje
 ├── main.cpp
 └── README.md
```

---

## ▶️ Programın Çalıştırılması

### 1️⃣ Derleme

Terminal veya komut satırında aşağıdaki komutu çalıştırın:

```bash
g++ main.cpp -o denklem
```

### 2️⃣ Çalıştırma

```bash
./denklem
```

---

## 🧪 Örnek Kullanım

**Girdi:**

```
a katsayisini giriniz: 1
b katsayisini giriniz: -3
c katsayisini giriniz: 2
```

**Çıktı:**

```
Diskriminant = 1
Bu denklemin iki farkli gercek koku vardir.
1. Kok: x1 = 2
2. Kok: x2 = 1
```

---

## 📘 Program Mantığı

1. Kullanıcıdan `a`, `b`, `c` değerleri alınır.
2. Diskriminant hesaplanır:

   ```
   diskriminant = b*b - 4*a*c
   ```
3. Koşullar:

   * Eğer diskriminant < 0 ise:

     * Gerçek kök yoktur.
   * Eğer diskriminant == 0 ise:

     * Tek bir gerçek kök vardır.
   * Eğer diskriminant > 0 ise:

     * İki farklı gerçek kök vardır.

---

## ⚠️ Dikkat Edilmesi Gerekenler

* `a` değeri **0 olmamalıdır**. Aksi halde denklem ikinci dereceden olmaz ve bölme hatası oluşabilir.
* Kullanıcı yalnızca sayısal değerler girmelidir.

---

## ✨ Geliştirme Önerileri

* `a = 0` kontrolü eklenebilir.
* Negatif girişler için hata mesajları geliştirilebilir.
* Grafik arayüz eklenebilir.
* Sonuçlar dosyaya kaydedilebilir.

---

## 👨‍💻 Geliştirici

**Diyorbek Nurmatov**
Bilgisayar Mühendisliği – Ödev-1

---

