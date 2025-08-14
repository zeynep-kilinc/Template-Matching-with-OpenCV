# Template Matching with OpenCV

Bu proje, Python ve OpenCV kullanarak **şablon eşleme (template matching)** yöntemini göstermektedir.  
Jupyter Notebook formatında hazırlanmış olup farklı `cv2.matchTemplate` yöntemleri kullanılarak eşleşme sonuçları görselleştirilmiştir.

## İçindekiler
- Şablon yükleme
- Farklı eşleme yöntemleri (`cv2.TM_CCOEFF`, `cv2.TM_CCORR`, `cv2.TM_SQDIFF`, vb.)
- Eşleşme sonuçlarının görselleştirilmesi
- En iyi eşleşme koordinatlarının bulunması

##  Gereksinimler
Bu projeyi çalıştırmak için aşağıdaki kütüphanelerin yüklü olması gerekir:

```bash
pip install opencv-python numpy matplotlib
