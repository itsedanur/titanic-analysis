 Titanic Survival Analysis
Bu proje, Titanic veri seti üzerinde yapılan kapsamlı bir veri analizi (EDA – Exploratory Data Analysis) çalışmasını içerir. Jupyter Notebook kullanılarak veri ön işleme, eksik değer analizi, görselleştirme ve temel istatistiksel incelemeler gerçekleştirilmiştir.

 Proje İçeriği
Bu repo aşağıdaki dosyaları içerir:
Titanic.ipynb — Tüm analizlerin yapıldığı Jupyter Notebook dosyası
train.csv — Model/analiz için kullanılan eğitim veri seti
test.csv — Test veri seti
.ipynb_checkpoints/ — Jupyter tarafından otomatik oluşturulan sistem klasörü

 Amaç
Titanic veri seti, veri bilimi dünyasında klasik bir başlangıç problemidir.
Bu proje ile:
Veri yapısını tanımak
Eksik değerleri tespit edip doldurmak
Kategorik ve sayısal değişkenleri incelemek
Outlier (aykırı değer) analizi yapmak
Korelasyon ve ilişkileri görselleştirmek
Seaborn ve Matplotlib ile veri keşfi yapmak
amaçlanmıştır.

 Uygulanan Veri Ön İşleme Adımları
✔ Eksik değerlerin sayılması ve doldurulması
✔ Age değişkeninin median + benzer özellik grupla doldurulması
✔ Embarked değişkeninin doldurulması
✔ Fare değişkeninin analiz edilmesi
✔ Outlier tespiti (IQR yöntemi ve boxplot ile)

 Yapılan Görselleştirmeler
Proje boyunca aşağıdaki grafik türleri kullanılmıştır:
Histogram
Boxplot
Countplot
Heatmap (korelasyon)
Pairplot (çoklu değişken incelemesi)
FacetGrid
Jointplot (kde, scatter, hex)

Kullanılan Kütüphaneler
pandas
numpy
matplotlib
seaborn

 Nasıl Çalıştırılır?
Repoyu klonlayın:
git clone https://github.com/itsedanur/titanic-analysis.git
Klasöre girin:
cd titanic-analysis
Notebook'u açın:
jupyter notebook
Titanic.ipynb dosyasını çalıştırın.

 Notlar
Bu proje veri analizi odaklıdır; modelleme (ML) içermemektedir.
İleride Logistic Regression, Random Forest gibi modeller eklenebilir.
 Geliştiren
Eda Nur Unal
