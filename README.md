# PyNar Kod Editörü Test Reposu

## 1. PyNar Editör nedir ve nereden öğreneceğim?

Pynar editör Python dili için yazılmış tamamen Türkçe desteki bir python editörüdür. Aşağıdaki linkten kullanma kılavuzunu okuyarak öğrenebilirsiniz. Kullanma kılavuzunda indirme linki de verilmektedir.

> http://www.pynar.org/help/

**Önemli Not: Pynar Editörü Windows işletim sistemine kurarken "Windows Kişisel Bilgisayarınızı Korudu" şeklinde bir uyarı gelebilir, bu pencerede "Ek Bilgi" bölümünü tıklayarak "Yine de çalıştır" diyerek kurulumu tamamlayabilirsiniz. Windows için sertifika almadığımız için bu uyarı çıkmaktadır, herhangi bir güvenlik sorunu yoktur.**

## 2. Hata Bildirimini nereden yapacağım?

Pynar Editörü test ederken karşılaştığınız hataları bu reponun sağ üst tarafındaki "Issues" bölümüne girebilirsiniz. ***Issue girişi yapabilmeniz için bir Github hesabınız olmalıdır.*** Issue ekranında "New Issue" diyerek bildirim yapabilirsiniz. "Title" bölümüne kısa bir başlık veriniz, "Leave a comment" bölümüne ise içeriğinizi yazınız. 3 tür içerik girilebilir, 1)Hata, 2)İyileştirme, 3)Yeni Özellik

![image](https://user-images.githubusercontent.com/854154/160295821-e29a87a4-63a2-4605-84fa-45dd38e8f710.png)

## 3. Nasıl Test edeceğim ?

1. bölümde linkini verdiğimiz pynar kılavuzdaki bütün adımları tek tek gerçekleştiriniz ve bunları yaparken herhangi sorun yaşamışsanız bu sorunu hata bildirimi olarak 4. bölümde yazdığımız şekilde tanımlayınız.

Bunların dışında editördeki bütün bileşenlerin herbirini tıklayarak veya sürükleyerek amacına uygun şekilde çalışma durumunu test etmeniz beklenmektedir.

Not: Pynar Editörün chatbot aracılığıyla kod hata düzeltme yeteneği sınırlıdır, karşılaşacağınız hataların yaklaşık %65'ini düzeltebilir. Bir kod içinde birden fazla hata varsa bunları düzeltemeyebilir. Testlerinizde bu konuyu dikkate alınız. Chatbot aracılığıyla düzeltilemeyen kod örneklerini de hata bildirimi olarak gönderebilirsiniz.

## 4. Hata Bildirimi formatı

Hata bildirimi yaparken mutlaka şu bilgileri de "Issue" metni içinde bildiriniz.

- Title
  - "Title" kısmına "Hata:" diyerek başlayınız.
- Comment içeriği
  - Kullandığınız işletim sistemi: Windows 7,8,10,11 veya Ubuntu Linux, Pardus Linux gibi. (**Pynar Editör MacOS işletim sistemini desteklemez!!**)
  - Hata hakkında yeterli miktarda açıklama, örneğin ne yaparken ortaya çıkıyor gibi.
  - Mümkünse hata ile ilgili ekran görüntüsü: Windows'un Ekran Alıntısı aracı ile ekran görüntüsü alarak Ctrl+V tuş kombinasyonu ile Issue metni içine yapıştırabilirsiniz. Ekranınınzın tamamının görüntüsünü almak yerine hatanın oluştuğu bölümün görüntüsünü almak daha çok tercih edilir.

## 5. İyileştirme önerisi

Pynar Editörde var olan bir özelliğin çalışma biçiminini daha anlaşılır olması için iyileştirme önerebilirsiniz. iyileştirme önerinizi de "Issue" bölümünden girebilirsiniz. İyileştirme öneriniz için de yeterli detay vermeniz beklenir. Gerekirse Paint programıyla yapılmış basit taslak çizimler yükleyebilirsiniz.

- Title
  - "Title" kısmına "İyileştirme:" diyerek başlayınız.

## 6. Yeni özellik önerisi 

Pynar editörde bulunmayan yeni bir özellik önerebilirsiniz. Öneriniz için de yeterli detay vermeniz beklenir. Gerekirse Paint programıyla yapılmış basit taslak çizimler yükleyebilirsiniz.

- Title
  - "Title" kısmına "Yeni Özellik:" diyerek başlayınız.

# PyNar Editör ile ilgili bilinen Sorunlar
 - Chatbot'un hata düzeltme yeteneği sınırlıdır. Bir kod içinde birden fazla hata varsa sadece biri için öneri yapabilir. Ayrıca Mantık hataları veya girinti (Indentation) hatalarını düzeltemez. Genellikle bir python komutunun yanlış veya eksik yazılması şeklindeki hataların önemli bir kısmını düzeltebilir. Bu tür hatalardan düzeltemediği varsa raporlayabilirsiniz.
 - PyNar Editör bütün hata mesajlarını Türkçe olarak vermelidir, Eğer bazı hata mesajları İngilizce olarak geliyorsa bunu raporlayın.
