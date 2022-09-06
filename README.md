# Introduction to Data Visualization with matplotlib

Bu repo yeni başlayanlar için [Matplotlib](https://matplotlib.org/) kütüphanesi ile Veri Görselleştirme için hazırlamış olduğum bir kaynak niteliğindedir. İçerisinde bir adet README dosyası, bir adet de introduction-to-data-visualization.ipynb barındırıyor.

![image](https://miro.medium.com/max/1400/1*u3QkXncCVoUk0ayFAYmYOQ.png)
---
## Öğreneceğimiz Alt Başlıklar
1. Matplotlib'e Giriş
2. Zaman serilerini çizme
3. Nicel karşılaştırmalar ve istatistiksel görselleştirmeler 
4. Görselleştirmeleri başkalarıyla paylaşma
---
## Veri Setlerini Tanıyalım
- climate_change: Yıllara göre bağıl sıcaklık değerleri ve karbondioksit seviyelerini içeren bir veri setidir.
- medals: Ülkelerin kazanmış oldukları altın, gümüş ve bronz madalya sayılarını barındıran bir veri setidir.
- summer_2016: Brezilya'da düzenlenen 2016 Yaz Olimpiyatlarında yarışan ülkelerin her branştan sporcuları ile ilgili bilgileri içeren bir veri setidir.
- austin_weather: ABD'nin Austin bölgesi için hava durumu hakkında sıcaklık ve yağış bilgilerini içeren bir veri setidir.
- seattle_weather: ABD'nin Seattle bölgesi için hava durumu sıcaklık ve yağış bilgilerini içeren bir veri setidir.
---
### *climate_change veri setini tanıyalım*
> *Sütun isimlerine ve bunları ne için kullanacağımıza bakalım*
* date: tarih
* co2: karbondioksit seviyesi
* relative_temp: bağıl sıcaklık miktarı
---
### *medals veri setini tanıyalım*
> *Sütun isimlerine ve bunları ne için kullanacağımıza bakalım*
* Bronze: Bronz madalya
* Gold: Altın madalya
* Silver: Gümüş madalya
---
### *summer_2016 veri setini tanıyalım*
> *Sütun isimlerine ve bunları ne için kullanacağımıza bakalım*
* Name: Sporcu isimleri
* Sex: Cinsiyet
* Age: Yaş
* Height: Sporcuların Boy uzunlukları
* Weight: Sporcuların Ağırlıkları
* Team: Ülke İsimleri
* NOC: Sporcunun milliyeti
* Games: Sporcunun katıldığı yarışma
---
### *austin_weather veri setini tanıyalım*
> *Sütun isimlerine ve bunları ne için kullanacağımıza bakalım*
* STATION: Yer, konum 
* MLY-PRCP-NORMAL: Her ayın ortalama yağış miktarlarını içerir.
* MLY-PRCP-25PCTL: Her ayın ilk çeyreklik yağış miktarlarını içerir.
* MLY-PRCP-75PCTL: Her ayın üçüncü çeyreklik yağış miktarlarını içerir.
* MLY-TAVG-NORMAL: Her ayın ortalama sıcaklık miktarlarını içerir.
* MLY-TAVG-STDDEV: Her ayın sıcaklıklarının standart sapmasını içerir.
---
### *seattle_weather veri setini tanıyalım*
> *Sütun isimlerine ve bunları ne için kullanacağımıza bakalım*
* STATION: Yer, konum 
* MLY-PRCP-NORMAL: Her ayın ortalama yağış miktarlarını içerir.
* MLY-PRCP-25PCTL: Her ayın ilk çeyreklik yağış miktarlarını içerir.
* MLY-PRCP-75PCTL: Her ayın üçüncü çeyreklik yağış miktarlarını içerir.
* MLY-TAVG-NORMAL: Her ayın ortalama sıcaklık miktarlarını içerir.
* MLY-TAVG-STDDEV: Her ayın sıcaklıklarının standart sapmasını içerir. 
---
