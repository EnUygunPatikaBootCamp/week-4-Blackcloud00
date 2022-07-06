# Week4Assignment

## ARAŞTIRMA (20 puan)
#### Test Driven Development ve Behaviour Driven Development arasındaki farkı açıklayınız.
- Test Driven Development geliştirme uygulamasıdır, Behaviour Driven Development ise bir ekip metodolojisidir. Test Driven Development'da geliştiriciler testleri yazarken, Behaviour Driven Development'da otomatik özellikler kullanıcılar ve testçiler tarafından oluşturulur.

#### Unit Test nedir? Unit Test nasıl yapılır?
Unit Test, bir yazılımın en küçük test edilebilir bölümlerinin, tek tek test edilip incelenmesi ve buradaki amaç yazılımın dooğru çalışması olduğu için bir yazılım geliştirme sürecidir.
- En küçük parçacığı test edilmeli
- Sadece bir senaryo test edilir.
- Kullanılan adımlar belirlenir.
- Test method ismi test edilen senaryonun yansıması olmalıdır.
- Test edilen kısım diğer kısımlardan bağımsız olmalıdır.
- Testlerimiz tam otomatik şekilde çalışmalıdır.
- Hızlı çalışabilmeli ve çabuk sonuçlar vermelidir.
- Okunaklı, anlaşılabilir ve sürdürebilir olmalıdır.
- Test başarısız olduğunda durmalı ve iyi bir hata raporu döndürmelidir. Bu hata raporunda neyi test ettin ? ne yapmalı ? beklenen çıktı neydi ve gerçekte ne yaptığıdır ?

## SYMFONY KONSOL UYGULAMASI OLUŞTURMA (20 puan)
1 ile N arası rastgele pozitif  tamsayıların olduğu bir array içinden en küçük ve en büyük sayıyı bulup, bu sayıları ekrana bastıran bir konsol uygulaması yazınız. Buradaki N değeri konsol uygulamasından parametrik olarak alınacaktır. Dizideki rastgele tamsayılar PHP’nin random fonksiyonuyla oluşturulabilir.

Örnek: 
Konsol Uygulaması için Input: 7
//Random array değerleri: Array = {1,6,743,24,132,54,9}

Çıktı: 
En Büyük Sayı: 743
En Küçük Sayı: 1

## SYMFONY WEB UYGULAMASI OLUŞTURMA (60 puan)
Ders esnasında composer ile oluşturmuş olduğumuz ve twig template içeren Symfony uygulamasını Repo’ya yükleyiniz. Twig template aşağıdaki özellikleri barındırmalıdır:
- En az 2 parametreyi controllerdan almalı (parametrelerden bir tanesi mutlaka array olmalı)
- Ena z 1 asset içermeli (css / js) ve template içinde bu asset kullanılmalı
- Template içinde controllerden alınan çıktı mutlaka döngüde bastırılmalı

