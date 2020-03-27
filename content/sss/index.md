---
title: "SSS"
layout: "single.html"
date: 2019-08-07T02:42:37+03:00
draft: false
---

**0. Zarola nedir?**

Zarola (İng. _diceware_), zarlar kullanarak, kolayca hatırlanabilir
güvenli parolalar oluşturmanızı sağlayan bir tekniktir. Zarola yöntemi
ile oluşturulan parolalar, ```mekik posta ekran semer toprak kalem
ustura``` gibi görünür.

**1. Zarolam ne kadar uzun olmalıdır?**

En az **yedi** kelime oluşturmanızı tavsiye ediyoruz. Kelimelerin
arasına veya sonuna ekstra karakterler eklemeniz parola güvenliğini
artıracaktır.
1996 yılında Matt Blaze, Whitfield Diffie, Ronald Rivest, Bruce
Schneier, Tsutomo Shimomura, Eric Thompson ve Michael Weiner'dan oluşan
bir grup bilgi güvenliği ve kriptografi uzmanından oluşan heyet,
"Simetrik Şifrelerde Yeterli Kurumsal Güvenliği Sağlamak için Minimum
Anahtar Uzunlukları" başlıklı raporunda, verileri 20 yıl daha güvende
tutabilmek için gereken minimum anahtar uzunluğunun 75 bit uzunluğunda
olması gerektiğini ifade etmişler ve yeni oluşturulan anahtarların en az
90 bit uzunluğunda olmasını tavsiye etmişlerdir.
Beş kelimelik bir Zarola en az 64.6 bit entropiye sahiptir. Altı
kelimede bu değer 77.5 bite, yedi kelimede 90.4 bite, sekiz kelimede 103
bite, dokuz kelimede 116 bite, on kelimede ise 129 bite çıkmaktadır.
Dört kelimelik bir parola yalnızca 51.6 bit entropiye sahiptir. Bu
parola, 24 adet grafik işlemci ile bir günden kısa bir süre içerisinde
kırılabilmektedir.
Eklediğiniz her bir rastgele karakter, yaklaşık olarak 10 bit entropi
eklemektedir.
Altı kelimelik bir parola, yüksek bütçeli bir kurum (örneğin devlet veya
çok uluslu bir şirket) tarafından kırılabilir durumdadır. Yedi kelimelik
bir parola ise, şimdilik bilinen hiçbir teknoloji tarafından kırılabilir
durumda değildir. Ancak 2030'larda yüksek bütçeli kurumlar tarafından
kırılabilir hale gelebilir. Sekiz kelimeli parolalar ise muhtemelen
2050'lere kadar güvenli olacaktır.
İstediğiniz güvenlik seviyesine göre parola seçmenizi tavsiye ediyoruz.
Örneğin kişisel Wi-Fi ağınızı altı kelimeli bir parolayla saklamayı
düşünebilirsiniz, çünkü sabit bir noktada ve sürekli denetiminizde
olacaktır. Ancak her an erişilebilen veya çalınabilecek mobil
cihazlarınızı daha güçlü bir Zarola ile saklamanız tavsiye edilir.
Kullandığınız GnuPG veya PGP anahtarınızı mutlaka ve mutlaka en az
**yedi** kelimeden oluşan Zarola ile korumanız şiddetle tavsiye
edilir.
Eğer bir kasada uzun süre saklayacağınız şifreli belgeler (örn. GnuPG
anahtarlarınızın kağıt yedekleri), elektronik imzalar, yok etmek veya
korumak istediğiniz diskler gibi noktalarda zarola kullanmayı
düşünüyorsanız, yedi kelimenin üzerine çıkmanız ve fazladan karakterler
eklenmeniz **şiddetle** tavsiye edilir.

**2. Parolamı bir yere yazmalı mıyım?**

Parolanızı ezberlediğinize emin olduktan sonra yazılı tutmayın.
Genellikle insanlar
parolalarını kaybetmekten ziyade unutmaktan korkar. Parolanızı
hatırlamak için hikayeleştirebilir, kelimeler arasında anlam ilişkileri
oluşturmayı deneyebilirsiniz. Parolanızı oluştururken ve ezberlerken
altında başka kağıt olmayan bir
kağıt parçasına yazabilirsiniz, ama ezberledikten sonra bu kağıt
parçasını yakarak imha etmeniz tavsiye edilir.

**3. Eğer birisi benim Zarola kullanığımı biliyorsa, kelime listesini
kullanarak parolamı bulamaz mı?**

Kısa cevap: Hayır, bulamaz.
Uzun cevap: Zarola yöntemi, bir saldırgan sizin bu yöntemi kullandığınızı,
hatta kaç kelime kullandığınızı biliyor olsa bile ziyadesiyle
güvenlidir. Zarola'nın güvenliği çok fazla kombinasyon olmasından gelir.
Bir zarola listesinde 7776 kelime bulunur. Eğer yedi kelimeli bir zarola
oluşturursanız,
**7776\*7776\*7776\*7776\*7776\*7776\*7776=2\*10<sup>27</sup> ihtimal
vardır (ortalama 2 oktilyon)**. Her bir parola denemesi için 10 ms
harcansa, bütün ihtimalleri denemek yaklaşık **10<sup>18</sup> yıl**
alacaktır (1 kentilyon). Evrenin oluşumundan bugüne yaklaşık 13,5 milyar
yıl geçtiğini varsayacak olursak, ne kadar büyük bir süre olduğunu hayal
edebilirsiniz.

**4. Oluşturduğum zarolaları nasıl hatırlayabilirim?**

Kelimeler arasında anlamsal ilişkiler oluşturmayı deneyebilir veya
parolanızı hikayeleştirebilirsiniz. Örneğin:

```sörf uçmuş lifli hijyen amblem gümrük parca```

şeklindeki bir parola için, "sörf yaparken uçmuş sörfçü, üzerine yapışan
lifli yosunları yıkarken, hijyen için kullandığı amblemli kabini
gümrükten parça parça geçirdiğini hatırladı." gibi bir hikaye
uydurabilirsiniz. Uzun görünebilir ama, birkaç kez okuduğunuzda
aklınızda kalacaktır.

**5. Hala zarolamı hatırlamakta güçlük çekiyorum. Ne yapmalıyım?**

Parolayı ezberleme süresi, birkaç saatten bir haftaya kadar kişiye göre
değişebilir. Eğer yine de ezberlemekte güçlük çekiyorsanız, yeni
bir parola oluşturmayı deneyin ama sadece beğenmediğiniz bir kelimeyi
değiştirmeyin.

**6. Parolamı unuttum! Verilerimi kurtarabilir miyim?**

Panik yapmayın ve şifrelenmiş dosyalarınızı silmeyin. İnsan beyni bazen
böyle oyunlar oynar. Yarın rastgele bir anda, örneğin yemek yerken veya
üç gün sonra ellerinizi yıkarken parolanızı bir anda
hatırlayabilirsiniz. Eğer birkaç kez yazdığınızda giremiyor iseniz,
harfleri tek tek girmeyi deneyebilirsiniz. Parolanızın bir harfini
yanlış hatırlıyor veya Türkçe karakter hatası yapıyor olabilirsiniz, bir
metin editörüne yazıp kontrol edebilirsiniz. Güçlü bir şifreleme
yazılımı üzerinde zarola kullanıyorsanız ve parolanızı gerçekten
unuttuysanız maalesef yapabileceğiniz hiçbir şey yok.

**7. Büyük harf kullanmalı mıyım? **

Zarola listesindeki her kelime küçük harfle yazılmıştır. Belirtilen
entropi değerleri, her şeyin küçük harflerle yazıldığı durumlarda
geçerlidir. Büyük harfler kullanarak, entropiyi artırabilirsiniz.
Eklediğiniz her büyük harf, yaklaşık olarak 3 ila 4 bit entropi ekler.
Ancak her büyük harf, Shift tuşuna basmayı gerektirir. Eğer parolanızın
yarısında büyük harf kullanacak olursanız, tuşa basışlarınız 1.5 kat
artacaktır. Bu da, tıklama başına oluşan entropiyi 2.67 bite
indirecektir. Yani tıklama başına küçük harfle yazdığınız paroladan daha
düşük bir entropi oluşacaktır.
Bunun haricinde, büyük harf kullanımı parolanızı hatırlamanızı
zorlaştıracaktır. Eğer zorundaysanız, kelimelerin ilk harfi gibi
hatırlaması kolay karakterleri büyük harf yapmanız şiddetle tavsiye edilir.

**8. Kelimeler arasına boşluk koymalı mıyım?**

Kelimeler arasına boşluk koymamak, parolayı zayıflatan bir durumdur.
Ancak boşluk tuşunun kendine has bir sesi olması ve baş parmak ile
basılması, parolanızın güvenliğini olumsuz etkileyebilir. Parolanızı
girerken sizi izleyen birisi, Zarolanızda kaç kelime kullandığınızı ve
kelimelerinizin uzunluklarını bu sayede takip edebilir. Bu yüzden
kelimelerin arasında, kullandığınız klavye düzeninde tek tıklamayla
basılabilecek bir özel karakter kullanmanız veya bir harf koymanız daha
uygun olacaktır. Bunun haricinde, bazı sistemler parolalarda boşluk
karakterini kullanmayı desteklememektedir.

**9. Parolamı hangi sıklıkla değiştirmeliyim?**

Parolanızı, değiştirme tercihi tehdit algınıza bağlıdır. Tavsiyemiz;
ortak alanlarda kullandığınız dizüstü ve cep telefonu gibi cihazların
erişimini sağlayan PIN/Parolalarını birkaç aylık sürelerde
değiştirmeniz, ortak alanlarda girdiğiniz tam disk şifreleme ve simetrik
şifrelerinizin parolalarını yıllık olarak ve GnuPG gibi asimetrik
şifreleme anahtarlarınızı da gerekmedikçe değiştirmemenizdir.

Parolanızı, şifreleme anahtarınızı her değiştirdiğinizde veya herhangi
bir güvenlik tehdidi algıladığınızda değiştirimenizi tavsiye ederiz.
Yeni bir parola oluşturmak birkaç dakikanızı alacaktır.

**10. Eğer başka birisinin parolamı bildiğinden şüphelenirsem ne
yapmalıyım?**

Parolanızı bir başkasının bildiğinden şüpheleniyorsanız, acilen
anahtarınızı ve parolanızı değiştirin.

**11. Herhangi bir sebepten mahkemeye çıkarsam parolamı vermek zorunda
mıyım?**

Türkiye Cumhuriyeti için konuşacak olursak, herhangi bir şekilde
mahkemede parolanızı vermek **zorunda değilsiniz**.

**12. Entropi nedir?**

Entropi, rastgeleliğin ölçütüdür. Bir sistemin rastgele olması,
çıktısının ne olacağının tahmin edilememesidir. Bunu bir bir dizi bozuk
para atışı ile hayal edebilirsiniz; arka arkaya atılacak 100 bozuk
paranın sonucunu doğru olarak kaç kere tahmin edebilirsiniz veya bir
atışı tahmin etmiş olmanız bir sonrakini de tahmin edebileceğiniz
anlamına gelir mi? Bu bakımdan bir olasılık kümesindeki her sonucun
olası olması bir saldırganın belirli bir özelliği hedefleyerek başarıya
ulaşmasını engeller. Bu sebeple Zarola parolaların güvenliği için
entropi kaynağı olarak zar kullanır.

**13. Bir parolanın entropisini nasıl hesaplayabilirim?**

Eğer bir parola n olasılıktan oluşan bir uzaydan seçildiyse ve bu
olasılıklar eşit olarak seçilebilir durumdaysa, entropi log2(n) değerini
taşır. x sembolden teşkil bir parolanın entropisi, x*log2(n) değeridir.
Örneğin, 16 harften oluşan rastgele oluşturulmuş bir parolanın entropisi
16*log2(26) yani 75,2 bit olacaktır. Eğer parolanın elemanları doğal
dillerden oluşuyorsa, durum daha karmaşık hale gelebilir. _Schneier's
Applied Cryptography_ kitabında İngilizce dilindeki yazılı bir metnin
ortalama entropisinin karakter başına 1.3 bit olduğu ifade edilmiştir.
Ancak bu varsayımı parolalara uygulamanın ne kadar doğru olduğu
tartışılabilir. Çünkü insanlar, zannedilenden daha çok tahmin
edilebilirdir. Genel anlamda insan faktörü devreye girdiğinde, parola
için entropi tahmini yapmak zorlaşır.
Gerçek anlamda parola güvenliği için, olabildiğince rastgelelik gerekir.
Zarola yöntemi bunun için iyi bir seçenektir, kelime başına 12.9 bit
entropi sunar.

**14. Kumarhane zarı nedir?**

Kumarhane zarları, ince işçilik ürünü olan şeffaf zarlardır. Tavla
zarlarından en önemli farkı, üzerindeki numaraların zara oyularak
yapılmamasıdır. Tavla zarları üzerine yapılan bir çalışmada, 4-5-6
numaralarının gelme olasılığının daha yüksek olduğu; bunun sebebinin ise
o numaraların bulunduğu yüzeylere numarayı yazmak için daha büyük
delikler açılması olduğu saptanmıştır (Guy Macon tarafından yapılan
araştırma). Ayrıca daha önce kullanılmış zarların kenarları zamanla
aşınacak ve olasılıkların eşitliğini bozacaktır. Tavla zarları şeffaf
olmadığından, üzerinde hile yapılması daha yüksek bir ihtimaldir. Olağan
zarlar kullanmanız zarolanızın gücüne çok etki edecek değildir ama yine
de kaliteli zarlar kullanmanız şayet mümkünse önerilir.

Bu sebeplerle, zarola oluştururken kaliteli zarlar kullanmanızı öneriyoruz.

**15. Zar atma uygulaması veya cihazı kullansam olur mu?**

Zar atma uygulamaları, **gerçek rastgelelik** içermez. Bu sebeple
parolalarınızı zar kullanarak oluşturmalısınız.

**16. Zarım yoksa ne yapabilirim?

Şayet zarınız yoksa, zarolanızı üretmek için bir başka entropi kaynağına
ihtiyaç duyacaksınız. Bunun için en kolay erişilebilir şey bozuk
paradır. 3 farklı boyutta bozuk parayı bir masada çevirerek ve aşağıdaki
tabloyu kullanarak zar atışlarına dönüştürebilirsiniz. Zar atmaktan
biraz daha uzun sürecek olsa da rastgele bir sonuç elde edeceğinizden
zarolanızın gücünde bir eksilme olmayacaktır.


