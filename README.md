# Spatial Transcriptomics — MERFISH Analizi

10x/MERFISH uzamsal transkriptomik verisinin Python (scanpy + squidpy)
ile uçtan uca analizi: kalite kontrol, kümeleme, hücre tipi anotasyonu
ve uzamsal istatistikler.

## Proje Amacı
Fare hipotalamusu MERFISH verisinde hücre tiplerini ve dokudaki
uzamsal organizasyonlarını ortaya çıkarmak.

## Repo Yapısı
- `notebooks/` — numaralı analiz notebook'ları (sırayla çalıştırılır)
- `src/` — tekrar kullanılan yardımcı fonksiyonlar
- `data/`, `figures/`, `results/` — yerel çıktılar (git'e dahil değil)

## Kurulum
```bash
pip install -r requirements.txt
```

## Notebook'ları Colab'da Aç
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KULLANICI_ADIN/REPO_ADIN/blob/main/notebooks/00_setup_and_data.ipynb)

## Analiz Adımları
1. Ortam kurulumu ve veri yükleme
2. Kalite kontrol
3. Kümeleme ve hücre tipi anotasyonu
4. Uzamsal istatistikler
5. Hücre-hücre iletişimi

## Veri Kaynağı
(Adım 3'te dolduracağız — veri seti ve orijinal yayın künyesi.)

## Lisans
MIT
