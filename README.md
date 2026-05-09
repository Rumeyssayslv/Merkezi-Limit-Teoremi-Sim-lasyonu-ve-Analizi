
Bu proje, Kocaeli Üniversitesi Yapay Zeka ve Makine Öğrenmesi Bölümü, Veri Bilimi İçin İstatistik dersi proje ödevi kapsamında hazırlanmıştır.

Projede Uniform, Exponential ve Poisson dağılımları üzerinden farklı örneklem boyutlarında ($n \in \{2,5,10,30,50,100\}$) veriler üretilmiş ve Merkezi Limit Teoremi'nin (CLT) geçerliliği istatistiksel testler (Shapiro-Wilk) ve görselleştirmeler ile doğrulanmıştır.

## Dosya Yapısı
* `main_analysis.ipynb`: Simülasyon kodları, istatistiksel testler ve proje raporunu içeren ana Jupyter Notebook dosyası.
* `report.pdf`: Notebook üzerinden dışa aktarılmış, projenin IMRaD formatındaki nihai raporu.
* `requirements.txt`: Projenin çalıştırılması için gerekli kütüphanelerin listesi.
* `data/`: Simülasyon verileri kod içinde üretildiği için bu klasör sembolik olarak boş bırakılmıştır.

## Kurulum ve Çalıştırma
1. Gerekli kütüphaneleri yüklemek için terminalde şu komutu çalıştırın:
   `pip install -r requirements.txt`
2. `main_analysis.ipynb` dosyasını Jupyter Notebook veya VS Code üzerinden çalıştırarak simülasyonu başlatabilirsiniz.