# YZM 411 Bilgisayarlı Görü — Ödev 1: Renk, Aydınlatma ve Örnekleme

**Öğrenci:** Osman ACAR — 230212016

Aynı masaüstü sahnesinin üç farklı ışık koşulunda (normal, gölge, telefon flaşı) çekilmiş fotoğraflarıyla:
renk eşiklerinin aydınlatmaya duyarlılığı (RGB/HSV), parlaklık ve gama dönüşümleri, 1/4 küçültmede bilgi kaybı.

## Dosyalar
| Dosya / klasör | İçerik |
|---|---|
| `YZM411_Odev1_1.ipynb` | Çalıştırılabilir defter (tahminler, kod, çıktılar) |
| `YZM411_Odev1_Rapor_LaTeX.pdf` | 2 sayfalık rapor |
| `Data/` | Kendi çektiğim özgün fotoğraflar: `Normal.jpg`, `Gölge.jpg`, `Parlak.jpg` |
| `outputs/` | Şekiller, CSV tabloları ve `sonuc_tablosu.csv` (tüm ham ölçümler) |

## Çalıştırma
1. `pip install numpy opencv-python pandas matplotlib ipykernel`
2. Defteri, `Data/` klasörüyle aynı dizinde açın.
3. *Restart → Run All*. Çıktılar `outputs/` klasörüne yazılır.

Test edilen sürümler: Python 3.13.1, NumPy 2.2.6, OpenCV 4.12.0, pandas 2.3.3, matplotlib 3.10.7 (Windows 10).

## Kaynak ve yapay zekâ beyanı
- Kaynak: YZM 411 ders notları, Hafta 1–2.
- Fotoğraflar ve ölçümler bana aittir; tüm çıktılar çalıştırılarak üretilmiştir.
- Claude (Anthropic) kullanıldı: defter iskeleti ve analiz kodları, piksel/ROI/eşik koordinatı önerileri,
  rapor ve analiz metni taslağı. Ayrıntılar raporun 9. bölümünde.
