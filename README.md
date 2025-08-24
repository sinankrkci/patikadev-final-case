# Akbank Teknoloji Okuryazarlığı – Kredi Kartı Harcamaları Veri Analizi

Bu proje, Akbank Teknoloji Okuryazarlığı kapsamında kredi kartı harcamaları verisinin analizini ve görselleştirilmesini içermektedir. Amaç, kullanıcıların harcama alışkanlıklarını anlamak ve veriden anlamlı içgörüler çıkarmaktır.

---

## İçerik

### 1. Jupyter Notebook: `final-case-veri-analizi.ipynb`
- **Veri Yükleme:** `users.csv` ve `transactions.csv` dosyaları yüklenir.
- **Veri Ön İşleme:** Eksik veriler, aykırı değerler ve veri tipleri kontrol edilip düzenlenir.
- **Veri Birleştirme:** Kullanıcı ve işlem verileri birleştirilir.
- **Keşifsel Veri Analizi (EDA):**
  - Kullanıcı ve işlem sayılarının özetlenmesi
  - Toplam harcama ve işlem dağılımlarının incelenmesi
  - Kategori bazında harcama analizleri
  - Zaman serisi analizleri (aylık/haftalık harcama trendleri)
  - En çok harcama yapılan kategoriler ve dönemler
  - Kullanıcı segmentasyonu (ör. en çok harcayan kullanıcılar)
- **Görselleştirme:** Matplotlib ve Seaborn ile grafikler oluşturulur.
- **Yorumlar:** Her analiz ve grafik sonrası kısa açıklamalar ve bulgular paylaşılır.

### 2. Power BI Raporu: `Sinan-Karakeci-Final-Case.pbix`
- Kredi kartı harcamalarına dair interaktif rapor ve görselleştirmeler içerir.
- Kullanıcı, kategori ve zaman bazında filtreleme ve detaylı inceleme imkanı sunar.

---

## Kurulum ve Kullanım

1. **Veri Dosyalarını Ekleyin:**  
   Proje dizinine `users.csv` ve `transactions.csv` dosyalarını yerleştirin.

2. **Gerekli Kütüphaneleri Kurun:**  
   Terminal veya Anaconda Prompt’ta aşağıdaki komutu çalıştırarak gerekli Python kütüphanelerini yükleyin:
   ```
   pip install pandas matplotlib seaborn jupyter
   ```

3. **Notebook’u Çalıştırın:**  
   ```
   jupyter notebook
   ```
   komutuyla Jupyter Notebook’u başlatın ve `final-case-veri-analizi.ipynb` dosyasını açarak hücreleri sırayla çalıştırın.

4. **Power BI Raporunu Açın:**  
   `Sinan-Karakeci-Final-Case.pbix` dosyasını Power BI Desktop ile açarak raporları inceleyebilirsiniz.

---

## Proje Yapısı

```
patikadev-final-case/
│
├── final-case-veri-analizi.ipynb
├── Sinan-Karakeci-Final-Case.pbix
├── users.csv
├── transactions.csv
└── README.md
```

---

