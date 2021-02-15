                                         BİLGİ EDİNME KANUNU IMPLEMENTASYONU 


4982 sayılı Bilgi Edinme Hakkı Kanunu kapsamında tanınan bilgi edinme hakkı ile kişiler, kurum ve kuruluşların kayıtlarında bulunan bilgi ve belgeleri talep etmek için kullanılabilir (dilekçe hakkı başka bir haktır).

 

Sistem pek çok yazılımın yanı sıra çalışan bir "Bilgi Edinme Modülü" yazılımı olacaktır. Sistemde 2 tip kullanıcı olacaktır:
1) Bilgi edinme başvurusu yapan
2) Bilgi edinme başvurusunu yöneten

 

Başvuru sahibi (1) "Gerçek" veya (2) "Tüzel" kişi olabilir. Herkes bilgi edinme hakkına sahiptir.

 

Bilgi edinme başvuruları 
(1) kamu kurum ve kuruluşları ve 
(2) kamu kurumu niteliğindeki meslek kuruluşlarına
yapılabilir. Bilgi edinme başvurusunu yöneten kişiler bu 2 tipteki kurumlarda bu başvuruları takip etmekle görevlendirilmiş çalışanlardır. 
Sistem bu 2 tipteki kuruluşların listesini, kurumun tipini (1 veya 2 tipinde), hangi kuruma bağlı olduğu vb bilgileri tutmalıdır. 
Bir kullanıcı tablosunda kurumdaki çeşitli yazılımlara giriş yapan kişilerin listesi olacaktır. Bu kişiler Personel tablosu ile ilişkili olacaktır.
Kullanıcı tablosuna bağlı bir yetki tablosunda kişinin Bilgi Edinme Modülü içinde yapmaya yetkili olduğu işlemlerin (örneğin çalıştırabileceği ekranlar) listesi tutulacaktır. Not: Kullanıcı tablosunda kullanıcı şifresi crypto edilmiş vaziyette tutulacaktır (Web Development dersinde bu işlerin gerçekte nasıl yapıldığını da görme şansınız olacak).

 

A) Bilgi edinme başvurusu yapılması
* Tüm başvurularda başvuru sahibinin Adı, Soyadı, Türk vatandaş olup olmadığı, Türk vatandaşı ise T.C. kimlik numarası, adresi (oturma yeri veya iş), telefonu (ev, iş, mobil), fax (opsiyonel), e-posta bilgileri, başvuruya hangi yolla cevap almak istediği (yazılı, elektronik), istenen bilgi veya belgeler ile ilgili talep açıklaması alınır.
* Tüzel kişi başvurularında başvuruyu yetkili kişi yapar ve tüzel kişinin ünvan bilgisi de alınır.
Bilgi edinme başvurusu 2 türlü yapılabilir (yazılı veya online): 
(1) Yazılı talebin elden kuruma teslim edilmesi
Kişi bilgi edinme başvurusunu imzalı olarak kuruma elden teslim eder. Başvuru kurumda çalışan yetkili bir kişi tarafından sisteme "Yeni başvuru" olarak eklenir. Başvuru otomatik olarak bir başvuru numarası alır, bu numara yazıcıdan alınan bir çıktı ile başvuru sahibine elden verilir.
* Başvuru sahibinden gerekli bilgileri içeren "bilgi edinme formunun" (gerçek veya tüzel kişi için) imzalı hali alınır 
(2) Online olarak (fax, e-mail, kurum web sayfasından)
a. Kişi bilgi edinme başvurusunu imzalı olarak kuruma fax yoluyla gönderir. Başvuru kurumda çalışan yetkili bir kişi tarafından sisteme "Yeni başvuru" olarak eklenir. Başvuru otomatik olarak bir başvuru numarası alır, bu numara SMS olarak başvuru sahibine iletilir.
b. Kişi bilgi edinme başvurusunu e-posta yoluyla kurumca ilan edilmiş bir e-posta adresine gönderir. Başvuru kurumda çalışan yetkili bir kişi tarafından sisteme "Yeni başvuru" olarak eklenir. Başvuru otomatik olarak bir başvuru numarası alır, bu numara e-mail ile başvuru sahibine iletilir.
c. Kişi kurum web sayfasındaki "Bilgi edinme ". Başvuru otomatik olarak bir başvuru numarası alır, bu numara ekranda gösterilir.
Not: Başvuru sahibi daha önce reddedilmiş bir başvuruyu Bilgi Edinme Değerlendirme Kurulu na ileterek itiraz edebilir. Kurul başvuru sahibinin lehine karar verirse başvuru sahibi kurul kararı ile yeni bir bilgi edinme başvurusu yapar, kurum bu başvuruyu bir daha reddedemez (15 gün içinde istenen bilgi belgeler başvuru sahibine verilir).

 

B) Bilgi edinme başvurusu takibi (bilgi edinme başvuru sahibi yapar)
Başvuru sahibi "başvuru numarası", "başvuru yapanın adı", "başvuru yapanın soyadı" ve "başvuru tarihi" bilgilerini web uygulamasından girerek başvurunun durumun takip edebilir (inceleme aşamasında, başka kuruma yönlendirildi, kabul edildi, reddedildi vb).

 

C) Bilgi edinme başvurusunun yönetilmesi (kurum çalışanı yapar)
Kurumda bilgi edinme başvuruların yöneten çalışan ilk başvuru önce olacak şekilde sonuçlanmamış başvuruları listeler (başvurular 15 gün içinde cevaplanmalıdır).
a. İstenen bilgi veya belge, başvurulan kurum ve kuruluştan başka bir yerde bulunuyorsa, başvuru dilekçesi bu kurum ve kuruluşa gönderilir ve durum ilgiliye yazılı veya elektronik olarak bildirilir (başka kuruma yönlendirilen başvurular 30 gün içinde cevaplanmalıdır).
b. Başvurunun yapıldığı kurum ve kuruluş, erişimine olanak sağladığı bilgi veya belgeler için başvuru sahibinden erişimin gerektirdiği maliyet tutarı kadar bir ücreti bütçeye gelir kaydedilmek üzere tahsil edebilir. Başvuru sahibi on beş iş günü içinde ücreti ödemezse talebinden vazgeçmiş sayılır.
c. Başvuru dilekçesi veya formuyla istenen bilgi veya belgeler, yeterince açık ve anlaşılır değilse, kurum ve kuruluşlar başvurunun hangi nedenlerle yeterince açık ve anlaşılır olmadığını başvuru sahibine bildirebilir ve ek bilgiler sunmasını isteyebilir.
d. Başvuru kabul edilip istenen bilgi belge başvuru sahibine iletilir ve başvuru sonuçlandırılır
Bilgi: veri
Belge: yazılı, basılı veya çoğaltılmış dosya, evrak, kitap, dergi, broşür, etüt, mektup, program, talimat, kroki, plân, film, fotoğraf, teyp ve video kaseti, harita, elektronik ortamda kaydedilen her türlü bilgi, haber ve veri taşıyıcıları 
e. Başvuru ret edilip başvuru sahibine ret sebebi (kanunun ilgili maddesi de belirtilerek) bildirilir
Kanun kapsamında ret sebepleri:
1) Devlet sırrı olan gizlilik dereceli bilgi veya belgeler
2) Ülkenin ekonomik çıkarlarına ilişkin bilgi veya belgeler
3) İstihbarata ilişkin bilgi veya belgeler
4) İdarî soruşturmaya ilişkin bilgi veya belgeler
5) Adlî soruşturma ve kovuşturmaya ilişkin bilgi veya belgeler
6) Özel hayatın gizliliği
7) Haberleşmenin gizliliği
8) Ticarî sır
9) Fikir ve sanat eserleri
10) Kurum içi düzenlemeler
11) Kurum içi görüş, bilgi notu ve tavsiyeler
12) Tavsiye ve mütalaa talepleri

 

D) Bilgi edinme başvurularının raporlanması (kurum çalışanı yapar)
Kurum ve kuruluşlar, bir önceki yıla ait olmak üzere;
a) Kendilerine yapılan bilgi edinme başvurularının sayısını,
b) Olumlu cevaplanarak bilgi veya belgelere erişim sağlanan başvuru sayısını,
c) Reddedilen başvuru sayısı ve bunların dağılımını gösterir istatistik bilgileri,
d) Gizli ya da sır niteliğindeki bilgiler çıkarılarak ya da bu nitelikteki bilgiler ayrılarak bilgi veya belgelere erişim sağlanan başvuru sayısını,
e) Başvurunun reddedilmesi üzerine itiraz edilen başvuru sayısı ile bunların sonuçlarını,
gösteren raporlar alınır.
