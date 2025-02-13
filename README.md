# Bootcamp QA Automation

## 📌 Deskripsi
Repositori ini berisi materi, contoh kode, dan latihan untuk Bootcamp QA Automation. Tujuannya adalah membantu peserta memahami konsep dasar hingga lanjutan dalam pengujian otomatisasi menggunakan berbagai tools dan framework.

## 🚀 Teknologi yang Digunakan
- **Java** (versi 17+)
- **TestNG** – Framework untuk pengujian otomatisasi
- **RestAssured** – Pengujian API
- **Selenium WebDriver** – Pengujian UI
- **Cucumber** – BDD Testing
- **Maven** – Dependency Management
- **Allure Report** – Reporting untuk hasil pengujian

## 📂 Struktur Proyek
```
bootcamp-qa-automation/
│── src/
│   ├── main/          # Kode utama (jika ada)
│   ├── test/          # Test cases
│   │   ├── api/       # Pengujian API
│   │   ├── ui/        # Pengujian UI
│   │   ├── bdd/       # Pengujian menggunakan Cucumber
│── pom.xml            # Konfigurasi Maven
│── README.md          # Dokumentasi proyek
```

## 📖 Instalasi dan Setup
### 1. Clone Repositori
```sh
git clone https://github.com/yourusername/bootcamp-qa-automation.git
cd bootcamp-qa-automation
```

### 2. Install Dependencies
Pastikan Anda memiliki **Java 17+** dan **Maven** terinstal, lalu jalankan:
```sh
mvn clean install
```

### 3. Menjalankan Test
#### 🔹 Menjalankan Semua Test
```sh
mvn test
```
#### 🔹 Menjalankan Test API Saja
```sh
mvn test -Dgroups=api
```
#### 🔹 Menjalankan Test UI Saja
```sh
mvn test -Dgroups=ui
```

## 📊 Melihat Hasil Pengujian dengan Allure
```sh
mvn allure:serve
```

## 👥 Kontributor
1. **Albert Simanjuntak** - *Instruktur QA Automation*
2. **Muhammad Asharul Ma'ali** - *Kontributor lainnya*

## 📜 Lisensi
Proyek ini menggunakan lisensi **MIT** – Bebas digunakan dan dikembangkan lebih lanjut.

## 🛠️ TODO


---
🎯 **Happy Testing & Automation!** 🤖✅

