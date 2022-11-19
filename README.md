# ARMUT_Association_Rule_Learning

Business Problem [EN]

Armut, the largest online service platform in Turkey, brings together those who provide services and those who want to receive services. 
It allows you to easily access services such as cleaning, renovation, transportation with a few taps on your computer or smartphone.
It is desired to create a product recommendation system with Association Rule Learning by using the data set containing the users who receive
services and the services and categories that these users have received.

İş Problemi [TR]

Türkiye’nin en büyük online hizmet platformu olan Armut, hizmet verenler ile hizmet almak isteyenleri buluşturmaktadır. 
Bilgisayarın veya akıllı telefonunun üzerinden birkaç dokunuşla temizlik, tadilat, nakliyat gibi hizmetlere kolayca ulaşılmasını sağlamaktadır.
Hizmet alan kullanıcıları ve bu kullanıcıların almış oldukları servis ve kategorileri içeren veri setini kullanarak
Association Rule Learning ile ürün tavsiye sistemi oluşturulmak istenmektedir.


Data Set Story (Veri Seti Hikayesi)

[EN]

The data set consists of the services that customers receive and the categories of these services. It contains the date and time information of each service received.
[TR]

Veri seti müşterilerin aldıkları servislerden ve bu servislerin kategorilerinden oluşmaktadır. Alınan her hizmetin tarih ve saat bilgisini içermektedir.

Veri Seti Hikayesi

UserId: Müşteri numarası

ServiceId: Her kategoriye ait anonimleştirilmiş servislerdir (Örnek : Temizlik kategorisi altında koltuk yıkama servisi).
Bir ServiceId farklı kategoriler altında bulanabilir ve farklı kategoriler altında farklı servisleri ifade eder. 
(Örnek: CategoryId’si 7 ServiceId’si 4 olan hizmet petek temizliği iken CategoryId’si 2 ServiceId’si 4 olan hizmet mobilya montaj)

CategoryId: Anonimleştirilmiş kategorilerdir (Örnek : Temizlik, nakliyat, tadilat kategorisi).

CreateDate: Hizmetin satın alındığı tarih


!!!!!!!!!!!!!!

Uyarı: Veri kümesini açık kaynak olmadığı için paylaşamayacağımı belirtmek isterim.

!!!!!!!!!!!!!!

Warning: I would like to point out that I cannot share the dataset because it is not open source.
