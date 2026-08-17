# 🏙️ New York City Airbnb Data Analysis & Market Exploration

![NYC Banner](nyc.jpg)

Bu proje, New York City (NYC) Airbnb pazarındaki kiralama dinamiklerini, fiyatlandırma stratejilerini, oda tipi dağılımlarını ve kullanıcı yorum trendlerini analiz etmek amacıyla hazırlanmış bir veri analitiği projesidir.

---

## 📌 Proje Özeti

Farklı formatlardaki (CSV, Excel, TSV) veri kaynakları birleştirilerek temizlenmiş, NYC'deki konaklama piyasasına dair temel içgörüler elde edilmiştir:
- Fiyatlandırma aralıkları ve lokasyon bazlı ortalama gecelik ücretler
- Oda tipi dağılımı (*Entire home/apt, Private room, Shared room*)
- İnceleme ve yorum trendleri (*Last review date analizi*)

---

## 📂 Dosya ve Dizin Yapısı

```text
├── data/
│   ├── airbnb_price.csv          # İlan fiyatları ve temel lokasyon verileri
│   ├── airbnb_room_type.xlsx     # Oda tipleri ve listeleme özellikleri
│   └── airbnb_last_review.tsv    # Son yorum tarihleri ve kullanıcı etkileşimleri
├── nyc.jpg                       # Görsel / Proje kapağı
├── notebook.ipynb                # Veri temizleme, EDA ve görselleştirme adımları
└── README.md                     # Proje dökümantasyonu


git clone [https://github.com/KULLANICI_ADIN/nyc-airbnb-analysis.git](https://github.com/KULLANICI_ADIN/nyc-airbnb-analysis.git)
cd nyc-airbnb-analysis
pip install pandas numpy matplotlib seaborn openpyxl jupyter
jupyter notebook notebook.ipynb
