ÖZET
Tübitak 2209-A kapsamında yaptığım bu projede üniversite öğrencilerinin okuma alışkanlıklarının araştırılacağı demografik sorular içeren bir anket formu oluşturulup öğrencilerin okuma alışkınlıklarının genel bir resmi veri görselleştirme teknikleri ile sunuldu.
Üniversite öğrencilerinin okudukları kitap sayısını etkileyen etkili faktörler, uygun sıfır yığılmalı regresyon analizleri R ve Python ile modellendi. Sonrasında okuma alışkanlığı üzerine etkisi olduğu düşünülen faktörler üzerinde istatistiksel sonuç çıkarımları yapıldı. Makine öğrenmesi algoritması ile Sınıflandırmalar yapılarak tahminler yapıldı ve çalışma genişletildi. 











1.Giriş

	Okuma alışkanlığı, bireylerin bilgi edinme, eleştirel düşünme ve kültürel birikimlerini artırma sürecinde büyük bir öneme sahiptir. Bilgi ve teknolojinin çok hızlı geliştiği günümüzde, bilgiye ulaşmanın en etkili ve kolay yolu okumaktır. Ancak, bu alışkanlığı kazanmak, birbirini etkileyen farklı etmenlerin bir araya gelmesiyle, kişinin, dönemler içerisinde ruhsal ve beyinsel olarak hazırlanmasını gerektiren bir süreçle ortaya çıkar. Okumak; sadece ders içerikli kitapları değil, ders dışı kitapları da okuyarak farklı bilgileri, kültürleri, zevkleri tadarak öğrenmektir. Özellikle üniversite öğrencileri, akademik başarılarının yanı sıra, sosyal ve kişisel gelişimlerini desteklemek amacıyla okuma faaliyetlerine yönelmektedir. Ancak, çağımızda dijital teknolojilerin hızla yaygınlaşması, geleneksel okuma alışkanlıklarında köklü değişikliklere yol açmıştır. Bu bağlamda, üniversite öğrencilerinin okuma alışkanlıklarını belirleyen faktörlerin incelenmesi, eğitim politikaları ve bireysel gelişim stratejileri açısından büyük bir gereklilik arz etmektedir.
	Okuma alışkanlığı kazanmanın temeli eğitim sisteminde gizlidir. Okul çağında bu alışkanlığı kazanamayan çocuğun, ileri dönemlerde kazanması zordur. Bu yüzden küçük yaşlardan itibaren çocuklara okumanın yanında farklı konularda araştırma alışkanlığı kazandırmak, okumayı severek yapmasını ve bunu boş zamanlarını değerlendirmek için kullandığı bir araç olarak görmesini sağlar. Ancak bu alışkanlığın kazanılmasında etkili olan; aile, okul ve yakın çevreyi göz ardı etmemek gerekir. Ailenin evde bir kitaplık oluşturması, çocuğun her an bu kitapları eline alabilecek yakınlıkta olması ve ailedeki büyüklerin bizzat okuyarak örnek olması, çocuğun kitaplara karşı olan sevgisini tetikleyecektir. 
	Üniversite öğrencilerinin okuma alışkanlıklarını etkileyen çeşitli faktörler bulunmaktadır. Bu faktörler, aile yapısından, bireysel özelliklere, eğitim ortamından, dijital medyanın etkisine kadar geniş bir yelpazede değerlendirilebilir. Özellikle dijital çağın getirdiği yenilikler ve değişimler, öğrencilerin okuma alışkanlıklarını yeniden şekillendirmektedir. Geleneksel basılı materyallerin yerini e-kitaplar, online makaleler ve sosyal medya platformlarında paylaşılan içerikler almaya başlamış, bu durum ise okuma alışkanlıklarının niteliği ve niceliği üzerinde önemli etkiler yaratmıştır. Bu değişim, aynı zamanda öğrencilerin bilgiye erişim hızını artırmış, ancak derinlemesine okuma ve analitik düşünme yeteneklerinde çeşitli zorluklara yol açmıştır.
	Eğitim kurumlarının ve eğitim politikalarının, öğrencilerin okuma alışkanlıklarını geliştirmede önemli bir rol oynadığı bir gerçektir. Bu nedenle, üniversite yönetimleri ve öğretim elemanlarının, öğrencilere okuma sevgisi kazandırmak ve bu alışkanlığı sürdürebilmeleri için uygun ortamlar ve kaynaklar sağlamaları gerekmektedir. Kitap kulüpleri, okuma etkinlikleri ve dijital okuma platformlarının teşvik edilmesi, öğrencilerin okuma alışkanlıklarını geliştirmelerine yardımcı olabilecek önemli adımlardır.
	Ayrıca, ailelerin ve sosyal çevrenin de öğrencilerin okuma alışkanlıkları üzerinde önemli bir etkisi bulunmaktadır. Çocukluk döneminde okuma alışkanlığı kazanan bireylerin, ileriki yaşamlarında da bu alışkanlıklarını sürdürmeleri daha olasıdır. Bu nedenle, ebeveynlerin ve yakın çevrenin, çocukların okuma alışkanlıklarını destekleyici tutumlar sergilemeleri önemlidir.
	Dijital medya ve teknolojinin hızla geliştiği günümüzde, öğrencilerin bilgiye erişim şekilleri de değişmiştir. İnternet ve sosyal medya, öğrencilerin bilgiye daha hızlı ve kolay ulaşmasını sağlamış, ancak aynı zamanda dikkat dağınıklığı ve yüzeysel okuma gibi sorunları da beraberinde getirmiştir. Bu nedenle, dijital okuryazarlık becerilerinin geliştirilmesi ve öğrencilerin eleştirel düşünme yeteneklerinin desteklenmesi, okuma alışkanlıklarının kalitesini artırmada önemli bir rol oynamaktadır.
	Sonuç olarak, bu çalışma, üniversite öğrencilerinin okuma alışkanlıklarını etkileyen faktörlerin daha iyi anlaşılmasına ve bu doğrultuda geliştirilecek eğitim politikaları ve stratejilerine katkı sağlamayı amaçlamaktadır. Üniversite öğrencilerinin okuma alışkanlıklarının desteklenmesi ve geliştirilmesi, hem bireysel gelişimlerine hem de toplumsal ilerlemeye önemli katkılar sağlayacaktır. Bu bağlamda, çalışma, üniversite yönetimleri, eğitim politikacıları ve öğretim elemanları için değerli bilgiler sunmayı hedeflemektedir.

	Araştırma bulgularının, üniversite öğrencilerinin okuma alışkanlıklarının geliştirilmesi adına yapılacak çalışmalara ışık tutması ve bu alanda gelecekte yapılacak araştırmalara yön vermesi umulmaktadır. Okuma alışkanlıklarının önemi göz önüne alındığında, bu çalışmanın bulguları, hem bireysel hem de toplumsal düzeyde önemli sonuçlar doğuracaktır. Bu nedenle, okuma alışkanlıklarının desteklenmesi ve geliştirilmesi, eğitim politikalarının ve stratejilerinin merkezinde yer almalıdır.
	Okumanın tanımlarına bakıldığında belli bir amaç doğrultusunda gerçekleştirilen eylem olarak nitelendirildiği görülebilmektedir. Toplumların kültürel, sosyal, ekonomik özelliklerine göre şekil alabilen okuma amaçları, bireyler tarafından benimsenirse ve bireyler kendilerine bir amaç edinirlerse okuma alışkanlığının kazanılması ve devam ettirilmesi çok daha mümkün hâle gelebilecektir. Okumanın amaçları şu başlılarla ele alınabilir: 
• Boş zamanları değerlendirmek, keyif almak için okuma, 
• Bilgi edinmek için okuma,
• Mesleki gelişimi sağlamak için okuma, 
• Sayılan üç okuma amacıyla farklı kombinasyonlar oluşturularak yapılan okuma
Bireylerin okuma amaçlarını belirlemeleri, onların okumaya karşı itici güçleri olacaktır. Amacı belli olan birey o amacını gerçekleştirmek için çaba harcar, zaman ayırır ve emeline ulaşır. Okuma amacı belli olan birey de hedeflerine ulaşabilmek için bir çaba içine girecektir.















2.Rapor dönemlerinde yapılan çalışmalar

İlk olarak ekte verilen anket formunda bulunan sorular için demografik çıkarımlar ilgili tablo ve grafikler ile değerlendirilmiştir.

       




Tablo 1: Cinsiyet dağılımına ilişkin tablo 
	Frekans	Yüzde
Erkek	113	34,7
Kadın	213	65,3
Toplam	326	100,0
   
Şekil 1: Cinsiyet dağılımına ilişkin pasta grafiği
Çalışmaya katılan 326 öğrenciden 113 (%34.7) ü erkek ve 213 (%65.3) ü kadındır (Tablo 1 ve Şekil 1).



Tablo 2: Kitap okuma alışkanlığına ilişkin tablo 
Kitap Okuma Alışkanlığınız Var mı?
	Frekans	Yüzde
Evet	193	59,2
Hayır	133	40,8
Toplam	326	100,0


Şekil 2: Kitap okuma alışkanlığına ilişkin pasta grafiği 

Çalışmaya katılan 326 öğrenciden 193(%59.2) kişinin kitap okuma alışkanlığı varken 133(%40,8) kişinin kitap okuma alışkanlığı yoktur (Tablo 2 ve Şekil 2).



Tablo 3: Kalınan yere ilişkin tablo
      Nerede Kalıyorsunuz?
	Frekans	Yüzde
Yurt	208	63,8
Ev Aile İle	93	28,5
Ev Arkadaşları ile	25	7,7
Toplam	326	100,0
















Şekil 3.1: Kalınan yere ilişkin pasta grafiği

Şekil 3.2: Kalınan yere ilişkin grafik
Çalışmaya katılan 326 öğrenciden 208(%63,8)’i yurtta, 93(%28,5)’ü Evde Ailesi İle, 25(%7,6)’i Evde Arkadaşları ile kalmaktadır.(Tablo 3, Şekil3.1 ve Şekil 3.2)
Tablo 4: Burs veya kredi alma durumuna ilişkin tablo
Burs veya kredi Alıyor musunuz?
	Frekans	Yüzde
Evet	217	66,6
Hayır	109	33,4
Toplam	326	100,0


Şekil 4: Burs veya kredi alma durumuna ilişkin pasta grafiği

Çalışmaya katılan 326 öğrenciden 217(%66,5)’si burs veya kredi alırken 109(%33,4)’u burs veya kredi almamaktadır (Tablo 4 ve Şekil 4).


Tablo 5: Spor yapmaya ilişkin tablo 
Spor Yapıyor musunuz?
	Frekans	Yüzde
Evet	134	41,1
Hayır	192	58,9
Toplam	326	100,0


Şekil 5: Spor yapmaya ilişkin pasta grafiği

Çalışmaya katılan 326 öğrenciden  134(%41,1)’ü spor yaparken, 192(%58,9)’si spor yapmamaktadır (Tablo 5 ve Şekil 5).

Tablo 6: Anne eğitim düzeyine ilişkin tablo
        Anne Eğitim Düzeyi
	Frekans	Yüzde
İlköğretim	175	53,7
Lise	78	23,9
Üniversite	72	22,1
Yüksek Lisans Ve Üzeri	1	0,3
Toplam	326	100,0















Şekil 6.1: Anne eğitim düzeyine ilişkin pasta grafiği

Şekil 6.2: Anne eğitim düzeyine ilişkin grafik
Çalışmaya katılan 326 öğrenciden 175(%53,6)’i Anne eğitim düzeyi ilköğretim, 78(%23,9)’i Lise, 72(%22,1)’si Üniversite ve 1(%0,3)’i Yüksek lisans ve üzeri olmaktadır (Tablo 6, Şekil 6.1 ve Şekil 6.2).
Tablo 7: Baba eğitim düzeyine ilişkin tablo  
Baba Eğitim Düzeyi
	Frekans	Yüzde
İlkokul	132	40,5
Lise	116	35,6
Üniversite	68	20,9
Yüksek Lisans ve Üzeri	10	3,1
Toplam	326	100,0


Şekil 7.1: Baba eğitim düzeyine ilişkin pasta grafiği

Şekil 7.2: Baba eğitim düzeyine ilişkin grafik 
Çalışmaya katılan 326 öğrencinin baba eğitim düzeyinin 132(%40,4)’si İlköğretim, 116(%35,5)’sı Lise, 68(%20,8)’i Üniversite ve 10(%3,1)’u Yüksek Lisans ve üzeri olmaktadır (Tablo 7, Şekil 7.1 ve Şekil 7.2).
Tablo 8: Ortalama günlük adım sayısına ilişkin tablo
Ortalama Günlük Adım Sayısı
	Frekans	Yüzde
0-5000 adım	66	20,2
5000-10000 adım	178	54,6
10000 ve üzeri	82	25,2
Toplam	326	100,0

Şekil 8.1: Ortalama günlük adım sayısına ilişkin pasta grafiği

Şekil 8.2: Ortalama günlük adım sayısına ilişkin grafik
Çalışmaya katılan 326 öğrenciden 178(%54,6)’i ortalama 5000-10000 adım, 82(%25,1) ‘si ortalama10000 ve üzeri adım ve 66(%20,2)’sı ortalama 0-5000 adım atmaktadır.(Tablo 8, Şekil 8.1 ve Şekil 8.2)
Tablo 9: Ailenin hangi bölgede yaşadığına ilişkin tablo
Aileniz Hangi Bölgede Yaşıyor
	Frekans	Yüzde
İç Anadolu	153	46,9
Akdeniz	57	17,5
Karadeniz	13	4,0
Marmara	45	13,8
Ege	31	9,5
Doğu Anadolu	12	3,7
Güney Doğu Anadolu	15	4,6
Toplam	326	100,0


Şekil 9: Ailenin hangi bölgede yaşadığına ilişkin grafik 
Çalışmaya katılan 326 öğrencinin ailesinden 153(%46,9)’ü İç Anadolu, 57(%17,5)’si Akdeniz, 45(%13,8)’i Marmara, 31(%9,5)’i Ege, 15(%4,6)’i Güney Doğu Anadolu, 13(%4)’ü Karadeniz, 12(%3,7)’si Doğu Anadoluda yaşamaktadır.


Tablo 10: Okula ulaşıma ilişkin tablo
       Okula Ulaşımı Nasıl Sağlıyorsunuz?
	Frekans	Yüzde
Toplu Taşıma	221	67,8
Kişisel Araç	12	3,7
Yürüyerek	93	28,5
Toplam	326	100,0

        
Şekil 10: Okula ulaşıma ilişkin pasta grafiği

Çalışmaya katılan 326 öğrenciden 221(%67,8)’i toplu taşıma, 93(%28,5)’ü yürüyerek, 12(%3,9)’si kişisel arak ile okula ulaşımını sağlamaktadır (Tablo 10 ve Şekil 10).


Tablo 11: Eğitim görülen fakülteye ilişkin tablo

Fakülteniz
	Frekans	Yüzde
Mühendislik Ve Fen Bilimleri	139	42,6
Eğitim Bilimleri	15	4,6
Edebiyat Bilimleri	86	26,4
İktisadi Ve İdari Bilimler	24	7,4
Sağlık Bilimleri	55	16,9
Güzel Sanatlar Bilimleri	7	2,1
Toplam	326	100,0


Şekil 11: Eğitim görülen fakülteye ilişkin grafik
Çalışmaya katılan 326 öğrenciden 139(%42,6)’u Mühendislik ve Fen Bilimleri, 86(%26,4)’sı Edebiyat, 55(%16,9)’i Sağlık Bilimleri, 24(%7,4)’ü İktisadi ve İdari Bilimler,15(%4,6)’Eğitim Bilimleri ve 7(%2,1)‘si Güzel Sanatlar Bilimleri Tabanlı fakültelerde okumaktadırlar (Tablo 11, ve Şekil 11).





Tablo 12: Alkol kullanımına ilişkin tablo
  Alkol Kullanıyor musunuz?
	Frekans	Yüzde
Evet	66	20,2
Hayır	260	79,8
Toplam	326	100,0



Şekil 12: Alkol kullanımına ilişkin pasta grafiği


Çalışmaya katılan 326 öğrenciden 66(%20,2)’sı alkol kullanırken 260(%79,8)’ı alkol kullanmamaktadır (Tablo 12 ve Şekil 12).


        Tablo 13: Sigara kullanımına ilişkin tablo 
        Sigara Kullanıyor musunuz?
	Frekans	Yüzde
Evet	89	27,3
Hayır	237	72,7
Toplam	326	100,0




Şekil 13: Sigara kullanımına ilişkin pasta grafiği 

Çalışmaya katılan 326 öğrenciden 89(%27,3)’u sigara kullanırken 237(%72,7)’si sigara kullanmamaktadır (Tablo 13 ve Şekil 13).


Tablo 14: Yemek ihtiyacını karşılamaya ilişkin tablo
Yemek İhtiyacınızı Nasıl Karşılıyorsunuz?
	Frekans	Yüzde
Üniversite/Fakülte Yemekhanesi	191	58,6
Hazır Yemekler	101	31,0
Evden Getiriyorum	34	10,4
Toplam	326	100,0


Şekil 14.1: Yemek ihtiyacını karşılamaya ilişkin pasta grafiği

Şekil 14.2: Yemek ihtiyacını karşılamaya ilişkin grafik
Çalışmaya katılan 326 öğrenciden 191(%58,6)’i Üniversite/Fakülte yemekhanesinden, 101(%31)’i hazır yemeklerden, 34(%10,4)’ü Evden getirerek yemek ihtiyacını karşılamaktadır (Tablo 14, Şekil 14.1 ve Şekil 14.2).


Tablo 15: Eğlence ve Sosyal aktivitelere katılma sıklığına ilişkin tablo
Sosyal Aktivitelere Katılma Sıklığı
	Frekans	Yüzde
0	20	6,1
1	38	11,7
2	70	21,5
3	107	32,8
4	50	15,3
5	41	12,6
Toplam	326	100,0


Şekil 15.1:  Eğlence ve Sosyal aktivitelere katılma sıklığına ilişkin pasta grafiği

Şekil 15.1:  Eğlence ve Sosyal aktivitelere katılma sıklığına ilişkin grafik
Çalışmaya katılan 326 öğrenciden eğlence ve sosyal aktivitelere katılma sıklığı 5 üzerinden 107(%32,8)’si 3, 70(%21,5)’i 2, 50(%15,3)’si 4, 41(%12,6)’i 5, 38(%11,7)’i 1 ve 20(%6,1)’si 0’dır (Tablo 15, Şekil 15.1 ve Şekil 15.2).
Tablo 16: GANO, aylık ortalama harcama, son bir ayda okunan kitap sayısı ve alttan alınan ders sayısına ilişkin tanımlayıcı istatistikler

	N	Ortalama	Medyan	Std. Sapma	Maksimum 	Minimum 
GANO	283	2,86	2,91	0,49	4	1,43
Aylık Ortalama Harcama	326	4369,5	4000	2555,67	9687,5	200
Son Bir Ayda Okuduğunuz Kitap Sayısı	326	2,04	2	2,05	20	0
Alttan Alınan Ders Sayısı	326	1,32	0	2.17	10	0

Ankete katılan 326 öğrencinin 283 tanesi genel ağırlıklı not ortalaması (GANO) sorusuna cevap vermiş ve ortalama GANO 2,86±0,49 olarak gözlemlenmiştir. Aylık ortalama harcama ortalaması 4369,5±2555,67; sor bir ayda okunan kitap sayısı ortalaması 2,04±2,05 ve alttan alınan ders sayısı 1,32±2,17 şeklinde tespit edilmiştir (Tablo 16).





3.Sonuç: 

Bu bölümde, testte elde edilen örneklem için istatistiksel bazı testler uygulanacaktır. Ayrıca kitap okuma sayısını etkileyen faktörlerin belirlenmesi amacıyla hem sıfır yığılmalı Poisson regresyon modeli hem de literatüre yeni kazandırılmış bir regresyon modeli ile belirlenecektir. 

3.1. İstatistiksel Testler

Bu alt bölümde, kitap okuma alışkanlığı ile demografik sorular arasındaki ilişkiler Ki-Kare bağılsızlık testi ile ve sürekli değişkenlerdeki ortalama farklılıkları t testi ile analiz edilmiştir. 

Tablo 17: Cinsiyetinin ile kitap okuma alışkanlığı arasındaki çapraz tablo
	Cinsiyet	Toplam
	Erkek	Kadın	
Kitap Okuma Alışkanlığı	Evet	n	54	139	193
		Beklenen n	66,9	126,1	193,0
	Hayır	n	59	74	133
		Beklenen n	46,1	86,9	133,0
Toplam	n	113	213	326
	Beklenen n	113,0	213,0	326,0
Ki-kare değeri: 9,330;p-değeri: 0,002;Cramér's V değeri: 0,169
p-değeri 0,002<0,10 olduğu için ve Cramér's V değeri 0,169 olduğu için, cinsiyet ile kitap okuma alışkanlığı arasında %90 güven aralığında istatistiksel olarak orta düzeyde anlamlı bir ilişki olduğunu söyleyebiliriz. Kadınların kitap okuma alışkanlığı olma oranı %72 iken, erkeklerin oranı %28 olarak görülmüştür. Bu oranlar, kadınların kitap okuma alışkanlığına sahip olma oranının erkeklerden daha yüksek olduğunu ve  orta düzeyde bir ilişki gücüne sahip olduğunu söyleyebiliriz.
Tablo 18: Spor yapma ile kitap okuma alışkanlığı arasındaki çapraz tablo
	Spor	Toplam
	Evet	Hayır	
Kitap Okuma Alışkanlığı	Evet	n	87	106	193
		Beklenen n	79,3	113,7	193,0
	Hayır	n	47	86	133
		Beklenen n	54,7	78,3	133,0
Toplam	n	134	192	326
	Beklenen n	134,0	192,0	326,0
Ki-kare değeri: 3,085; p-değeri: 0,079; Cramér's V değeri: 0,097

p değeri 0,079<0.10 olduğu için ve cramer’s V değeri 0,097 olduğu için spor ile kitap okuma alışkanlığı arasında istatistiksel olarak çok zayıf düzeyde anlamlı bir ilişki olduğunu %90 güven aralığında söyleyebiliriz. Spor yapanların kitap okuma alışkanlığı olma oranı %45,3 iken spor yapmayanların %54,7 olduğu görülmüştür. Bu oranlar, spor yapmanın kitap okuma alışkanlığı ile pozitif bir ilişki içinde olduğunu gösterir. Ancak, bu fark istatistiksel olarak anlamlı olsa bile, bu ilişkinin gücünün zayıf olduğunu söyleyebiliriz.
Tablo 19: Baba eğitim düzeyi ile kitap okuma alışkanlığı arasındaki çapraz tablo

	Baba_egitim	Toplam
	İlkokul	Lise	Üniversite	Yüksek Lisans Ve Üzeri	
Kitap Okuma Alışkanlığı	Evet	71	68	50	4	193
	Hayır	61	48	18	6	133
Toplam	132	116	68	10	326
Ki-kare değeri: 8,897; p-değeri: 0,031

p-değeri 0.031<0.10 olduğu için baba eğitim düzeyinin kitap okuma alışkanlığı üzerinde istatistiksel olarak anlamlı bir etkisi olduğu %90 güven aralığında söyleyebiliriz. Çapraz tablolamada görüldüğü üzere en çok kitap okuma alışkanlığı olan öğrenciler 71 öğrenci ile baba eğitim düzeyi ilk okul olan bireyler fakat baba eğitim düzeyi ilkokul olan bireylerde bu oran %51 iken üniversite olanlarda iste bu oran 	%73 görülmektedir. Yani baba eğitim düzeyi üniversite olan öğrencilerin kitap okuma alışkanlığının daha fazla olduğunu %90 güven aralığında söyleyebiliriz.

Tablo 20: Sigara kullanımı ile kitap okuma alışkanlığı arasındaki çapraz tablo
	Sigara Kullanımı	Toplam
	Evet	Hayır	
Kitap Okuma Alışkanlığı	Evet	n	55	138	193
		Beklenen n	52,7	140,3	193,0
	Hayır	n	34	99	133
		Beklenen n	36,3	96,7	133,0
Toplam	n	89	237	326
	Beklenen n	89,0	237,0	326,0
Ki-kare değeri: 0,341; p-değeri: 0,559

Ki-kare testi sonucunda p-değeri 0,559 >0,10 olduğu için sigara kullanımının kitap okuma alışkanlığı üzerinde istatistiksel anlamda bir etkisinin olmadığını %90 güven aralığında söyleyebiliriz.


Tablo 21: Kitap okuma alışkanlığı GANO üzerindeki etkisinin incelenmesi
	Kitap Okuma Alışkanlığı	N	Mean	Std. Deviation	Std. Error Mean
GANO	Evet	167	2,9117	,45354	,03510
	Hayır	116	2,7947	,54478	,05058
t-test istatistik değeri: 1,964; p-değeri: 0,051

p-değeri 0,051<0,10 olduğu için kitap okuma alışkanlığı olan ve olmayan grupların genel akademik not ortalamaları arasında fark olduğunu %90 güven aralığında söyleyebiliriz. Kitap okuma alışkanlığı olan öğrencilerin ortalama GANO’ları 2,91 iken olmayanlarınki 2,79 dur yani genel akademik başarı arttıkça kitap okuma alışkanlığının da arttığını söyleyebiliriz.


3.2. Sıfır Yığılmalı Regresyon Modeli Genel Yapısı ve Uygulaması

Bağımlı değişkenin sayma verisi olarak gözlemlendiği durumlarda klasik regresyon modelleri bağımsız değişkenin bağımlı değişken üzerine olan etkisini açıklamak için yeterli olmayacaktır. Bu durumlarda sayma verileri için kurulan ve “count” regresyon modeli olarak ifade edilen regresyon modellerin kullanılması gerekir. Count regresyon modeli denince akla gelen ilk regresyon modeli Poisson regresyon modelidir. Poisson regresyon modeline alternatif geometrik regresyon modeli, negatif binom regresyon modeli gibi birçok regresyon modeli mevcuttur. Bağımlı değişkenin yoğun bir şekilde sıfır içerdiği durumlar için bu bahsedilen Poisson, geometrik ve negatif binom regresyon modelleri yetersiz kalmakta ve bunlar yerine sıfır yığılmalı regresyon modelleri tercih edilmektedir. Burada yanıt değişken adaylarımızdan biri olan kitap okuma sayısı sıfır yoğun bir şekilde içerebileceğinden sıfır yığılmalı regresyon modellerinin kullanılması muhtemeldir. Burada sıfır yığılmalı bir regresyon modelinin genel yapısından bahsedilecektir:
başarı olasılığına dahip bir Bernoulli rasgele değişkeni ve ise 0,1,2… değerlerini alabilen kesikli bir rasgele değişken olsun.  ve  bağımsız olmak üzere aşağıdaki  rasgele değişkeni tanımlansın

                                                                                                (1)
Bu durumda  rasgele değişkenini sıfır yığılmalı dağılım olarak adlandırılır ve olasılık fonksiyonu 
                                                        (2)
şeklindedir. Sıfır yığılmalı  rasgele değişkenini beklenen değeri ve varyansı 
           
şeklinde olup burada  ve   rasgele değişkeninin beklenen değer ve varyansıdır.  eşitlik (2) de olasılık fonksiyonu verilen  rasgele değişkeni ve   bağımsız olmak üzere sıfır yığılmalı regresyon modeli 
                                                                                              (3)
şeklinde verilen fonksiyonel ifadeler ile sunulmaktadır. Burada  dir. 
 bağımsız ve farklı dağılımlara sahip olasılık fonksiyonu eşitlik (2) de verilen rasgele değişkenler olsun. Eşitlik (3) kullanılarak olabilirlik fonksiyonu
              
şeklinde verilebilir. Burada   ve  dır. Bu durumda ya ilişkin en çok olabilirlik tahmini
                
ile ifade edilir. Bu projede parametre tahminleri ve gerekli prosedürler yukarıda anlatılan metodoloji ışığında gerçekleştirilecektir. En çok olabilirlik tahmin edicisi elde edilirken R programındaki optim kodundan ve python programındaki sklearn kütüphanesinden  faydalanacaktır.

Uygulama bölümü için kitap okuma sayıları bağımlı değişken olarak alınırken cinsiyet, anne eğitim düzeyi, baba eğitim düzeyi, aylık harcama, burs durumu, konaklama, sigara kullanımı, alkol kullanımı, spor durumu, günlük adım sayısı, alttan aldığı ders sayısı ve aylık katıldığı sosyal faaliyet sayısı değişkenleri bağımsız değişken olarak değerlendirilmiştir. Uygulama için sıfır yığılmalı regresyon modeli dışında Karakaya (2023) tarafından tanıtılan sıfır yığılmalı Poisson Epanechnikov-exponential (PEE) regresyon modeli de kullanılmıştır. Sıfır yığılmalı regresyon modeli için detaylara Karakaya (2023) çalışmasından erişilebilmektedir. Parametre tahminin için en çok olabilirlik (EÇO) yöntemi kullanılmıştır. Ayrıca model parametrelerinin anlamlılığı için gerekli p-değerleri rapor edilmiştir (p-değeri<0.10 ise katsayı anlamlıdır). Regresyon modeline ilişkin sonuçlar verilmiştir.


Kitap okuma alışkanlığı etkileyen faktörlerin R ile sıfır yığılmalı Poisson regresyon ve sıfır yığılmalı Cos-Poisson regresyon modeli ile belirlenmesi ;
	Sıfır yığılmalı Poisson 	Sıfır yığılmalı PEE
	EÇO	p-değeri	EÇO	p-değeri
Sabit	0,015	0,975	-0,057	0,935
Cinsiyet	0,260	0,018	0,408	0,011
Anne eğitim	0,046	0,414	0,048	0,581
Baba eğitim	-0,079	0,179	-0,061	0,483
Harcama	0,081	0,651	0,111	0,681
Burs	0,052	0,588	0,002	0,989
Konaklama	0,054	0,471	0,028	0,795
Sigara	-0,026	0,813	-0,058	0,733
Alkol	0,315	0,022	0,288	0,162
Spor	-0,222	0,028	-0,287	0,059
Adım	0,038	0,620	-0,005	0,963
Alttan ders	-0,018	0,397	-0,031	0,333
Sosyal faaliyet	0,008	0,821	0,045	0,396
Sıfır enflasyon için model katsayıları
Sabit	-0,750	0,825	-9,291	0,857
Cinsiyet	-2,281	0,001	-20,679	0,067
Anne eğitim	0,258	0,494	10,151	0,222
Baba eğitim	-0,783	0,140	-15,142	0,124
Harcama	-0,811	0,452	2,009	0,893
Burs	0,953	0,121	11,566	0,352
Konaklama	0,271	0,600	4,159	0,406
Sigara	0,574	0,541	-5,700	0,589
Alkol	-0,419	0,653	2,934	0,630
Spor	1,607	0,029	30,252	0,243
Adım	-0,170	0,735	-17,053	0,191
Alttan ders	-0,057	0,750	-38,532	0,065
Sosyal faaliyet	-0,312	0,253	5,946	0,132
Akeike Bilgi Kriteri	1263,801	1255,116



R ile yapılan regresyon modellerinden yeni regresyon modeli olan PEE regresyon modelinin Poisson regresyon modelinden daha iyi sonuç verdiği Akaike bilgi kriterine göre tespit edilmiştir. PEE regresyon modeline göre cinsiyet ve spor kitap okuma üzerinde etkili değişkenler olarak gözlemleniştir. Kadınların erkeklere daha fazla kitap okuduğu, ayrıca spor yapan kişilerin spor yapmayanlara göre daha fazla kitap okuduğu sonucuna varılmıştır.

Python ile ise poisson regresyon modeli ridge regresyon modeli ve ols (en küçük kareler) regresyon modeli kıyaslanarak bu veriye en uygun modelin ols olduğu belirlenip ols regresyon modeline göre kitap okuma üzerinde etkili değişkenler gözlenmiştir. 
Değişken	EÇO (Katsayı)	p-değeri
Sabit (const)	1.8834	0.000
Cinsiyetiniz Nedir?	-0.2563	0.000
Anne Eğitim Düzeyi Nedir?	-0.0156	0.681
Baba Eğitim Düzeyi Nedir?	-0.0622	0.088
Aylık Ortalama Harcamanız Ne Kadar?	-1.809e-05	0.140
Burs veya kredi alıyor musunuz?	-0.0337	0.599
Nerede kalıyorsunuz?	0.0123	0.794
Sigara Kullanıyor Musunuz?	0.0625	0.407
Alkol Kullanıyor Musunuz?	-0.0724	0.417
Spor yapıyor musunuz?	0.1833	0.005
Günlük kaç adım atarsınız?	-0.0323	0.465
Alttan aldığınız ders sayısı ne kadar?	0.0242	0.078
Aileniz hangi bölgede yaşıyor?	-0.0250	0.130
Eğlence ve Sosyal Aktivitelere Katılım (0-5)	-0.0025	0.915
Hangi Tabanlı Fakültede Eğitim Görüyorsunuz?	0.0110	0.563


Python ile yapılan bu OLS regresyon modeline göre de cinsiyet ve spor kitap okuma üzerinde etkili değişkenler olarak gözlemleniştir. Kadınların erkeklere daha fazla kitap okuduğu, ayrıca spor yapan kişilerin spor yapmayanlara göre daha fazla kitap okuduğu sonucuna burada da varılmıştır.
Bu çalışmanın ardından yine python programından bir random forest sınıflandırma algoritması kullanılarak tahminlerde verideki değişkenlerin değişimine göre tahminlerde bulunan bir çalışma yapılmıştır. 








