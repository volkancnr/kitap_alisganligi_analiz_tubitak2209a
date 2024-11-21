ÖZET:

Tübitak 2209-A kapsamında yaptığım bu projede üniversite öğrencilerinin okuma alışkanlıklarının araştırılacağı demografik sorular içeren bir anket formu oluşturulup öğrencilerin okuma alışkınlıklarının genel bir resmi veri görselleştirme teknikleri ile sunuldu.
Üniversite öğrencilerinin okudukları kitap sayısını etkileyen etkili faktörler, uygun sıfır yığılmalı regresyon analizleri R ve Python ile modellendi. Sonrasında okuma alışkanlığı üzerine etkisi olduğu düşünülen faktörler üzerinde istatistiksel sonuç çıkarımları yapıldı. Makine öğrenmesi algoritması ile Sınıflandırmalar yapılarak tahminler yapıldı ve çalışma genişletildi. 



Rapor dönemlerinde yapılan çalışmalar

İlk olarak ekte verilen anket formunda bulunan sorular için demografik çıkarımlar ilgili tablo ve grafikler ile değerlendirilmiştir.

       
![image](https://github.com/user-attachments/assets/6dbe748a-1043-41f4-9d27-dbcfc8d77185)


![image](https://github.com/user-attachments/assets/604014c4-4922-4bfc-b1a6-f803e467e33c)

Çalışmaya katılan 326 öğrenciden 113 (%34.7) ü erkek ve 213 (%65.3) ü kadındır (Tablo 1 ve Şekil 1).


![image](https://github.com/user-attachments/assets/2d499691-cf2f-49c6-84a7-7670c04e6ac9)

Çalışmaya katılan 326 öğrenciden 193(%59.2) kişinin kitap okuma alışkanlığı varken 133(%40,8) kişinin kitap okuma alışkanlığı yoktur (Tablo 2 ve Şekil 2).
![image](https://github.com/user-attachments/assets/c68e7894-2aa9-4cbd-aca2-05e0cf75fc49)
![image](https://github.com/user-attachments/assets/2db4444f-e81c-4b99-8862-32601f297e83)

Çalışmaya katılan 326 öğrenciden 208(%63,8)’i yurtta, 93(%28,5)’ü Evde Ailesi İle, 25(%7,6)’i Evde Arkadaşları ile kalmaktadır.(Tablo 3, Şekil3.1 ve Şekil 3.2)

![image](https://github.com/user-attachments/assets/20a7b8a9-fecf-42a6-9279-1b0b97e485a0)

Çalışmaya katılan 326 öğrenciden 217(%66,5)’si burs veya kredi alırken 109(%33,4)’u burs veya kredi almamaktadır (Tablo 4 ve Şekil 4).

![image](https://github.com/user-attachments/assets/17fca389-c2de-42a3-9197-705a3dc5521d)

Çalışmaya katılan 326 öğrenciden  134(%41,1)’ü spor yaparken, 192(%58,9)’si spor yapmamaktadır (Tablo 5 ve Şekil 5).

![image](https://github.com/user-attachments/assets/2b67d04d-85d0-42e3-a7ba-2e893fda8fff)

Çalışmaya katılan 326 öğrenciden 175(%53,6)’i Anne eğitim düzeyi ilköğretim, 78(%23,9)’i Lise, 72(%22,1)’si Üniversite ve 1(%0,3)’i Yüksek lisans ve üzeri olmaktadır (Tablo 6, Şekil 6.1 ve Şekil 6.2).

![image](https://github.com/user-attachments/assets/aa5710c7-66e4-41dd-981f-58c89f02c3f5)

Çalışmaya katılan 326 öğrencinin baba eğitim düzeyinin 132(%40,4)’si İlköğretim, 116(%35,5)’sı Lise, 68(%20,8)’i Üniversite ve 10(%3,1)’u Yüksek Lisans ve üzeri olmaktadır (Tablo 7, Şekil 7.1 ve Şekil 7.2).

![image](https://github.com/user-attachments/assets/f8cdf829-caac-41aa-a037-6e2a2323d09b)

Çalışmaya katılan 326 öğrenciden 178(%54,6)’i ortalama 5000-10000 adım, 82(%25,1) ‘si ortalama10000 ve üzeri adım ve 66(%20,2)’sı ortalama 0-5000 adım atmaktadır.(Tablo 8, Şekil 8.1 ve Şekil 8.2)

![image](https://github.com/user-attachments/assets/73f95561-f7ee-49fb-9a83-d816132ed1c6)

Çalışmaya katılan 326 öğrencinin ailesinden 153(%46,9)’ü İç Anadolu, 57(%17,5)’si Akdeniz, 45(%13,8)’i Marmara, 31(%9,5)’i Ege, 15(%4,6)’i Güney Doğu Anadolu, 13(%4)’ü Karadeniz, 12(%3,7)’si Doğu Anadoluda yaşamaktadır.

![image](https://github.com/user-attachments/assets/911816dc-86ba-4f1e-a818-9885ae751394)

Çalışmaya katılan 326 öğrenciden 221(%67,8)’i toplu taşıma, 93(%28,5)’ü yürüyerek, 12(%3,9)’si kişisel arak ile okula ulaşımını sağlamaktadır (Tablo 10 ve Şekil 10).

![image](https://github.com/user-attachments/assets/af7c985c-a257-4c7f-96b1-e8bda5d2114a)

Çalışmaya katılan 326 öğrenciden 139(%42,6)’u Mühendislik ve Fen Bilimleri, 86(%26,4)’sı Edebiyat, 55(%16,9)’i Sağlık Bilimleri, 24(%7,4)’ü İktisadi ve İdari Bilimler,15(%4,6)’Eğitim Bilimleri ve 7(%2,1)‘si Güzel Sanatlar Bilimleri Tabanlı fakültelerde okumaktadırlar (Tablo 11, ve Şekil 11).

![image](https://github.com/user-attachments/assets/87009b4b-bd3a-4c45-81e0-c0abc821902f)

Çalışmaya katılan 326 öğrenciden 66(%20,2)’sı alkol kullanırken 260(%79,8)’ı alkol kullanmamaktadır (Tablo 12 ve Şekil 12).

![image](https://github.com/user-attachments/assets/d3cc0d91-b364-4f77-b38e-27026c6c8fe1)

Çalışmaya katılan 326 öğrenciden 89(%27,3)’u sigara kullanırken 237(%72,7)’si sigara kullanmamaktadır (Tablo 13 ve Şekil 13).

![image](https://github.com/user-attachments/assets/fd5d5306-746e-4a72-8b2a-d4df3256a475)

Çalışmaya katılan 326 öğrenciden 191(%58,6)’i Üniversite/Fakülte yemekhanesinden, 101(%31)’i hazır yemeklerden, 34(%10,4)’ü Evden getirerek yemek ihtiyacını karşılamaktadır (Tablo 14, Şekil 14.1 ve Şekil 14.2).

![image](https://github.com/user-attachments/assets/ddc91d2d-46bd-4575-aca0-7a842fd89289)
![image](https://github.com/user-attachments/assets/4720c139-ebf3-4c1a-8c90-fc2e5c5bb677)
Çalışmaya katılan 326 öğrenciden eğlence ve sosyal aktivitelere katılma sıklığı 5 üzerinden 107(%32,8)’si 3, 70(%21,5)’i 2, 50(%15,3)’si 4, 41(%12,6)’i 5, 38(%11,7)’i 1 ve 20(%6,1)’si 0’dır (Tablo 15, Şekil 15.1 ve Şekil 15.2).

![image](https://github.com/user-attachments/assets/06690238-66ff-4a90-b1cb-b055fc65a1f4)

Ankete katılan 326 öğrencinin 283 tanesi genel ağırlıklı not ortalaması (GANO) sorusuna cevap vermiş ve ortalama GANO 2,86±0,49 olarak gözlemlenmiştir. Aylık ortalama harcama ortalaması 4369,5±2555,67; sor bir ayda okunan kitap sayısı ortalaması 2,04±2,05 ve alttan alınan ders sayısı 1,32±2,17 şeklinde tespit edilmiştir (Tablo 16).

 İstatistiksel Testler

Bu alt bölümde, kitap okuma alışkanlığı ile demografik sorular arasındaki ilişkiler Ki-Kare bağılsızlık testi ile ve sürekli değişkenlerdeki ortalama farklılıkları t testi ile analiz edilmiştir. 

![image](https://github.com/user-attachments/assets/a76e5940-f710-44de-890a-a7be54e563b0)

p-değeri 0,002<0,10 olduğu için ve Cramér's V değeri 0,169 olduğu için, cinsiyet ile kitap okuma alışkanlığı arasında %90 güven aralığında istatistiksel olarak orta düzeyde anlamlı bir ilişki olduğunu söyleyebiliriz. Kadınların kitap okuma alışkanlığı olma oranı %72 iken, erkeklerin oranı %28 olarak görülmüştür. Bu oranlar, kadınların kitap okuma alışkanlığına sahip olma oranının erkeklerden daha yüksek olduğunu ve  orta düzeyde bir ilişki gücüne sahip olduğunu söyleyebiliriz.

![image](https://github.com/user-attachments/assets/f7e237b8-45d1-4f1e-b448-ec387a0fc2ae)

p değeri 0,079<0.10 olduğu için ve cramer’s V değeri 0,097 olduğu için spor ile kitap okuma alışkanlığı arasında istatistiksel olarak çok zayıf düzeyde anlamlı bir ilişki olduğunu %90 güven aralığında söyleyebiliriz. Spor yapanların kitap okuma alışkanlığı olma oranı %45,3 iken spor yapmayanların %54,7 olduğu görülmüştür. Bu oranlar, spor yapmanın kitap okuma alışkanlığı ile pozitif bir ilişki içinde olduğunu gösterir. Ancak, bu fark istatistiksel olarak anlamlı olsa bile, bu ilişkinin gücünün zayıf olduğunu söyleyebiliriz.

![image](https://github.com/user-attachments/assets/d6bfa94c-3bc8-493a-af7b-ecc940dbfd52)

p-değeri 0.031<0.10 olduğu için baba eğitim düzeyinin kitap okuma alışkanlığı üzerinde istatistiksel olarak anlamlı bir etkisi olduğu %90 güven aralığında söyleyebiliriz. Çapraz tablolamada görüldüğü üzere en çok kitap okuma alışkanlığı olan öğrenciler 71 öğrenci ile baba eğitim düzeyi ilk okul olan bireyler fakat baba eğitim düzeyi ilkokul olan bireylerde bu oran %51 iken üniversite olanlarda iste bu oran %73 görülmektedir. Yani baba eğitim düzeyi üniversite olan öğrencilerin kitap okuma alışkanlığının daha fazla olduğunu %90 güven aralığında söyleyebiliriz.

![image](https://github.com/user-attachments/assets/5b073c79-0144-4913-909b-f302348f7299)

Ki-kare testi sonucunda p-değeri 0,559 >0,10 olduğu için sigara kullanımının kitap okuma alışkanlığı üzerinde istatistiksel anlamda bir etkisinin olmadığını %90 güven aralığında söyleyebiliriz.

![image](https://github.com/user-attachments/assets/49cb27db-d562-436f-97c1-e0e6af2213c8)

p-değeri 0,051<0,10 olduğu için kitap okuma alışkanlığı olan ve olmayan grupların genel akademik not ortalamaları arasında fark olduğunu %90 güven aralığında söyleyebiliriz. Kitap okuma alışkanlığı olan öğrencilerin ortalama GANO’ları 2,91 iken olmayanlarınki 2,79 dur yani genel akademik başarı arttıkça kitap okuma alışkanlığının da arttığını söyleyebiliriz.

Sıfır Yığılmalı Regresyon Modeli Uygulaması

En çok olabilirlik tahmin edicisi elde edilirken R programındaki optim kodundan ve python programındaki sklearn kütüphanesinden  faydalanacaktır.

Uygulama bölümü için kitap okuma sayıları bağımlı değişken olarak alınırken cinsiyet, anne eğitim düzeyi, baba eğitim düzeyi, aylık harcama, burs durumu, konaklama, sigara kullanımı, alkol kullanımı, spor durumu, günlük adım sayısı, alttan aldığı ders sayısı ve aylık katıldığı sosyal faaliyet sayısı değişkenleri bağımsız değişken olarak değerlendirilmiştir. Uygulama için sıfır yığılmalı regresyon modeli dışında Karakaya (2023) tarafından tanıtılan sıfır yığılmalı Poisson Epanechnikov-exponential (PEE) regresyon modeli de kullanılmıştır. Sıfır yığılmalı regresyon modeli için detaylara Karakaya (2023) çalışmasından erişilebilmektedir. Parametre tahminin için en çok olabilirlik (EÇO) yöntemi kullanılmıştır. Ayrıca model parametrelerinin anlamlılığı için gerekli p-değerleri rapor edilmiştir (p-değeri<0.10 ise katsayı anlamlıdır). Regresyon modeline ilişkin sonuçlar verilmiştir.

![image](https://github.com/user-attachments/assets/bdf66892-5b5e-4f27-8f83-85df6f63c383)

R ile yapılan regresyon modellerinden yeni regresyon modeli olan PEE regresyon modelinin Poisson regresyon modelinden daha iyi sonuç verdiği Akaike bilgi kriterine göre tespit edilmiştir. PEE regresyon modeline göre cinsiyet ve spor kitap okuma üzerinde etkili değişkenler olarak gözlemleniştir. Kadınların erkeklere daha fazla kitap okuduğu, ayrıca spor yapan kişilerin spor yapmayanlara göre daha fazla kitap okuduğu sonucuna varılmıştır.

Python ile ise poisson regresyon modeli ridge regresyon modeli ve ols (en küçük kareler) regresyon modeli kıyaslanarak bu veriye en uygun modelin ols olduğu belirlenip ols regresyon modeline göre kitap okuma üzerinde etkili değişkenler gözlenmiştir. 

![image](https://github.com/user-attachments/assets/133e2dc8-1027-4127-b5b9-6321c1382234)


Python ile yapılan bu OLS regresyon modeline göre de cinsiyet ve spor kitap okuma üzerinde etkili değişkenler olarak gözlemleniştir. Kadınların erkeklere daha fazla kitap okuduğu, ayrıca spor yapan kişilerin spor yapmayanlara göre daha fazla kitap okuduğu sonucuna burada da varılmıştır.
Bu çalışmanın ardından yine python programından bir random forest sınıflandırma algoritması kullanılarak tahminlerde verideki değişkenlerin değişimine göre tahminlerde bulunan bir çalışma yapılmıştır. 


