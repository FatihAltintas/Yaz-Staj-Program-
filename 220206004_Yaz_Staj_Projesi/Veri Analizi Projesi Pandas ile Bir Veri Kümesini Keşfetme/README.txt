Titanic Veri Analizi Projesi
Proje Özeti
Bu proje, Titanic gemisindeki yolcuların verilerini analiz etmek amacıyla hazırlanmıştır. Analiz sürecinde Pandas, Matplotlib ve Seaborn gibi Python kütüphaneleri kullanılmıştır. Proje, veri temizleme, keşifsel veri analizi (EDA) ve veri görselleştirme adımlarını içermektedir.

Veri kümesi, Titanic gemisinde seyahat eden yolcuların demografik bilgilerini, bilet sınıfını ve hayatta kalma durumlarını içermektedir. Analizler sonucunda, hayatta kalma oranlarının cinsiyet, bilet sınıfı, yaş gibi faktörlere göre nasıl değiştiği incelenmiştir.

Proje Dosyaları
titanic_analysis.ipynb: Projenin Jupyter Notebook dosyasıdır. Bu dosya, veri yükleme, veri temizleme, EDA ve görselleştirme adımlarını içerir.
titanic_analysis.py: Jupyter Notebook'ta bulunan tüm kodları içeren Python betiği.
README.md: Proje hakkında genel bilgi ve çalıştırma talimatları içeren dosya.
Gereksinimler
Bu projeyi çalıştırmak için aşağıdaki Python kütüphanelerine ihtiyacınız olacak:

pandas
matplotlib
seaborn
Bu kütüphaneleri, pip kullanarak yükleyebilirsiniz:

pip install pandas matplotlib seaborn
Projenin Çalıştırılması
Projeyi çalıştırmak için aşağıdaki adımları izleyin:

Veri Kümesini İndirme:

Veri kümesi, Titanic gemisindeki yolcuların bilgilerini içermektedir. Bu veri kümesini yüklemek için internet bağlantısına ihtiyacınız olacak.
Jupyter Notebook'u Çalıştırma:

Jupyter Notebook'u açın ve titanic_analysis.ipynb dosyasını yükleyin.
Her hücreyi sırasıyla çalıştırarak veri yükleme, veri temizleme, EDA ve görselleştirme adımlarını gerçekleştirin.
Python Betiği Çalıştırma:

Alternatif olarak, tüm analizleri bir Python betiği olarak çalıştırmak isterseniz, titanic_analysis.py dosyasını çalıştırabilirsiniz:

python titanic_analysis.py
Proje Yapısı
Veri Temizleme: Eksik değerlerin doldurulması ve gereksiz sütunların kaldırılması.
Keşifsel Veri Analizi (EDA): Temel istatistiksel özetler ve kategorik değişkenlerin dağılımı.
Veri Görselleştirme:
Hayatta kalma durumunun, bilet sınıfının, cinsiyetin ve yaşın görselleştirilmesi.
Yaş, bilet fiyatı ve hayatta kalma durumu arasındaki ilişkilerin incelenmesi.
Sonuçlar
Titanic veri kümesi üzerinde yapılan analizler, hayatta kalma oranlarının cinsiyet, bilet sınıfı ve yaş gibi faktörlere göre değiştiğini göstermiştir. Kadın yolcuların hayatta kalma oranı erkeklere göre daha yüksek olup, birinci sınıf yolcuların hayatta kalma oranı da diğer sınıflara göre daha yüksektir. Ayrıca, yaş ve bilet fiyatının hayatta kalma üzerinde etkisi olduğu görülmüştür.