# EmployeeManagement

# 👩‍💼 Employee Management

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)](https://www.python.org/) [![Google Colab](https://img.shields.io/badge/Colab-Notebook-yellow?logo=googlecolab)](https://colab.research.google.com/) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

📘 **Açıklama**  
Bu proje, Google Colab üzerinde çalışan bir Employee Management (Çalışan Yönetimi) uygulamasıdır. Çalışan bilgilerini ekleme, listeleme ve yönetme gibi işlemleri yapar. Python ile geliştirilmiş olup, basit veri işlemleri için idealdir.  

---

## 🛠️ Kullanılan Teknolojiler

- 🐍 **Python 3.9+**
- 📂 **Google Colab**
- 🧮 **Pandas**
- 📝 (Varsa) Diğer kütüphaneler: NumPy, Matplotlib vb.

---

## 🚀 Kurulum ve Çalıştırma

### 1️⃣ Notebook’u Aç
👉 [**Google Colab’da Açmak için Tıkla**](https://colab.research.google.com/drive/1cl1OP6MeSw4cf24EAY6GI2Ft13WNmH6K)  

Alternatif: Notebook’u bilgisayarına indirip [Jupyter Notebook](https://jupyter.org/) ile açabilirsin.

---

### 2️⃣ Drive’ı Bağla

Notebook’u çalıştırmadan önce Drive erişimini aktif et:  

```python
from google.colab import drive
drive.mount('/content/drive')
```

Drive bağlantısını onayladıktan sonra çalışma klasörünü ayarla:  

```python
import os
os.chdir('/content/drive/MyDrive/employee-management')
```

---

### 3️⃣ Gereken Paketleri Kur

Notebook’ta aşağıdaki hücreyi çalıştırarak bağımlılıkları yükleyin:  

```python
!pip install pandas
```

---

### 4️⃣ Notebook’u Çalıştır

Her hücreyi sırayla çalıştır (Shift + Enter) ve çıktıları gözlemle.

---

## 📁 Dosya Yapısı

```
📁 employee-management/
├── employee_management.ipynb   # Google Colab Notebook
├── requirements.txt            # Bağımlılıklar (varsa)
└── README.md                   # Proje açıklaması
```

---

## ✨ Katkıda Bulun

Katkı yapmak ister misin?  
1. Repoyu forkla 🍴  
2. Yeni bir branch oluştur: `feature/yenilik`  
3. Değişiklikleri commit et ✅  
4. Pull request gönder 📥

---

## 📜 Lisans

Bu proje [MIT Lisansı](LICENSE) ile korunmaktadır.
