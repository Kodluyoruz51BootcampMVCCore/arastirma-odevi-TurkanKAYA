                                            SOLİD PRENSİPLERİ
1- Single-Responsibility Principle(Tek Sorumluluk Prensibi)Bir Sınıfın ya da fonksiyonun,metodun tek bir görevi, sorumluluğu olmalıdır. Başka sınıfların görevlerini gerçekleştirmemelidir.
     Örneğin: Aşçı sınıfında YemekYap metodu olur ama malzemeAl metodu olmaz ama Aşçı istese malzemeyi gidip alabilir. Lakin bu aşçının ana görevi değildir dolayısıyla gerek yoktur.
2- Open-Closed Principle(Açık Kapalı Prensibi):   Open-Closed prensibi kısacası bir programın,applicationun veya objelerin ya da entitylerin geliştirilmeye açık ancak değiştirmeye kapalı olduğunu belirtir. İnterface ve abstract sınıflar kullanılarak istenen eklemeler yapılabilir.
Örnek : Bir şirkette çalışanların emeklilik günleri hesaplanacak Her sınıf ayrı ayrı tanımlı işçi, memur vs ve her birinin bilgileri,işe giriş tarihleri sınıflarında tanımlı. Ne zaman emekli olduklarını hesaplamak için sgkHesap isimli sınıfımızda hesap metodu var. Patronumuz dedi ki buraya yöneticileri de ekle yöneticilerin de emeklilik günleri hesaplansın. Bunun için sadece sgkHesap kısmına if else koşullarıyla kontrol edilip hesaplatılmak istenen gün sayısının sahibi olan kişinin ne olduğu tespit edilerek yaptırılabilir.Hesap aynı hesap sadece değişen şey obje.

3 — Liskov Substitution Principle ( Liskov’un Yerine geçme Prensibi):Bir ana sınıftan ya da sınıflardan türetilen sınıfların bir üst hiyerarşideki sınıfların yerine geçmesini esas alan bir prensiptir.
örnek : Dörtgenler Üst sınıf ve kare alt sınıf olsun. dörtgen sınıfında tanımlı boyut değiştir metodu uzun kenarı 300 ve kısa kenarı 100 yapsın. Kare sınıfını bunun yerine geçirdiğiniz zaman(Kare de bir dörtgendir) karenin tüm kenarları eşit olduğu için bu metodu karşılayamaz ve bu yüzünden LSPye uymaz.
4- Interface Segregation Principle ( Arayüz Ayrımı Prensibi): Bir arayüze gerekli olmayan eklentilerin eklenmemesini belirten bir prensiptir. Arayüzde o an sadece kullanılacak olan eklentilerin ekli olması gerektiğini savunur.
Örnek : İki boyutlu şekiller sınıfında hacim isimli bir metod tanımlamak. İki boyutlu şekillerin hacmi olmadığı için bu metod gereksizdir.
5- Dependency Inversion Principle ( Bağımlılıkların Terslenmesi Prensibi)
Varlıklar(Alt sınıflar ve Üst sınıflar) somut olmayan soyutlamalara bağlı olmalıdır. Üst seviye modülün düşük seviye modülüne bağlı olmamasını, ancak soyutlamalara bağlı olması gerektiğini belirtir. Alt sınıflarda yapılan değişiklikler üst sınıfları etkilememelidir.
Örnek : Yönetici ve işçi diye bir sınıfımız olsun. Yönetici sınıfımızın yeterince karmaşık olduğunu ve hem yöneticiye ait bilgilerin hem de işçiler üzerinde etki edebilecek metotları olduğunu düşünelim. Süper işçi diye yeni bir sınıf tanımladık. Ancak şu an yönetici sınıfındaki metotlar sadece işçilere hizmet veriyor ve bu durumda yönetici sınıfında çok büyük değişikliğe gitmemiz gerekecek çünkü oradaki metotların hepsi sadece işçiler için tasarlandı. Eğer dependency inversion prensibine uyulsaydı karmaşıklık minimum düzeye indirilebilirdi ve üst sınıf (yönetici) alt sınıf olan süper işçilere bağlı olmazdı.
  
                    
                
                           MİCROSOFT BUİLD 2020 YENİLİKLERİ

Azure Synapse Link : Maliyetleri düşüren ve zaman kazandıran Azure Synapse Link, veri hareketlerini yönetmeye gerek kalmadan müşterilerin değerli bilgiler elde etmesini sağlıyor.
 Fluid Framework: açık kaynak platformu olarak geliştiricilere sunulmaya başlandı. Böylece Office.com ve Web için Outlook’taki Fluid bileşenleri de son kullanıcılara sağlanmış oldu.
Azure Machine Learning ve OSS araçlarına getirilen yeniliklerle müşterilerin yapay zekâ modellerini daha sorumlu bir şekilde kullanmasına yardımcı olmak için yeni Responsible ML. araçları sunuldu. Bu araç, model yorumlama yeteneğini geliştirerek veri güvenliğini ve kullanıcı gizliliği garanti altına alacak, yapay zeka sistemlerinin geliştirilmesinde sorumluluk anlayışını güçlendirecek.
 Visual Studio Codespaces: VS Codespaces, geliştiricilerin dakikalar içinde tamamen yapılandırılmış geliştirme. ortamları oluşturması için bulutun gücünden faydalanıyor.

                       

                   Takip Ettiğim Kişiler

Sadi Evren Şeker:  2000 yılında, Yeditepe Üniversitesi Bilgisayar Mühendisliği bölümünün tek mezunu olarak lisansını tamamlamıştır. Ardından yine aynı bölümde okulumuzda yüksek lisans yapmış ve araştırma görevlisi olarak çalışmıştır. 2003 yılındaki mezuniyetinde önce İstanbul Teknik Üniversitesi’nde ikinci bir yüksek lisansprogramı olarak, “Bilim Teknoloji ve Toplum” programına kayıt yaptırmış, 2004 yılında bu programı tamamlamıştır. 2005-2010 yılları arasında Yıldız Teknik Üniversitesi’nde doktorasını tamamlamış ve bu sürede çeşitli üniversitelerde ders vermiştir. Doktora sonrası araştırma için bulunduğu UT Dallas’ta Yönetim Bilişim Sistemleri alanına geçiş yapmış ve doçentliğini bu alanda almıştır. 2015 yılından beri bir sosyal sorumluluk projesi olarak yürüttüğü “Bilgisayar Kavramları” isimli YouTube kanalında bilişim alanında eğitim ve ropörtaj videoları yayınlamaktadır. 2017 yılında kurduğu BILKAV Eğitim ve Danışmanlık A.Ş.’nin ardından geçtiğimiz sene Optiwisdom şirketinin de CEO’su olarak çalışmalarına devam etmektedir.
Murat Yücedağ: Yazılım Mühendisliği   mezunudur.Udemy'de 14 farklı kursta 30 binden fazla öğrenci (Udemy 1'den fazla kursa kayıtlı öğrencileri tek öğrenci olarak sayıyor) ile 4.72 eğitmen puan ortalaması ile oldukça güzel geri dönüşler alarak eğitim alanında çalışmalarımı sürdürmektedir.  Profesyonel olarak yazılım alanında projeler yürütmenin yanında aynı zamanda bu alanda eğitmenlik de yapmaktadır.Üniversite sürecimde İstanbul TeknoPark, Yıldız TeknoPark ve Elazığ TeknoPark'larda bulunan birçok farklı şirkette, alanında lider kıdemli yazılımcılarla beraber projelerde farklı roller üstlenme şansına erişmiştir.
Hakim olduğu programlama dilleri arasında C#, SQL, ASP.Net, C ağırlıklı olmak üzere ek olarak HTML, CSS, Bootstrap, MVC, Entity Framework, DevExpress, .NetCore, Bunifu gibi teknolojileri de kullanabilmektedir.
2014'ten itibaren aktif olarak YouTube kanalına yüklediği 1300'den fazla eğitim videosu ile yazılımda fırsat eşitliği ve toplumda yazılım farkındalığı oluşturmak gayesiyle çıktığı yolda 10.000.000'u aşan izlenme ve 79.000'den fazla kanal abonelerim ile birlikte ciddi bir kitleye ulaştımıstır. Ve Aralık 2019 itibari ile Youtube'da bulunan ücretsiz eğitim videosu sayısı  1300'ü geçti.
Ayrıca Ekim 2018'de Dikeyeksen Yayınevi ile C# Eğitim Kitabı ve Yeni Başlayanlar & Çocuklar İçin Kodlama adıyla 2 farklı kitap çalışması gerçekleştirmiştir.
Sadık Turan: İlgi alanı daha çok Web Uygulamaları geliştirmek üzerine olmakla birlikte son zamanlarda ilgilendiği teknolojiler ; Asp net core mvc, Xamarin, Python, ve Javascript tabanlı geliştirilen uygulamalardır. Dolayısıyla NodeJs, Angular, React ve VueJs bir hayli ilgisiniçekmektedir.





                               Devler Azureda Eğitimleri
Kubertenes Atölyeleri:
16 Nisan Perşembe
17:00 - 18:30	Pamir Erdem - Microsoft Türkiye, Azure Teknik Eğitmen
Containerlar ve Kubernetes
Kubernetes İş Yükleri
30 Nisan Perşembe
17:00 - 18:30	Pamir Erdem - Microsoft Türkiye, Azure Teknik Eğitmen
Kubernetes Kod Geliştirme Araçları
Kubernetes ve Akıllı Ağ Yapıları ( Service Mesh)

DevOps Atölyeleri:
21 Nisan Salı
17:00 - 18:00	Mehmet Kut - Microsoft Türkiye, Azure Teknik Eğitmen
DevOps Kültürü ve Azure DevOps
28 Nisan Salı
17:00 - 18:30	Mehmet Kut - Microsoft Türkiye, Azure Teknik Eğitmen
Azure DevOps ile uygulama derleme ve dağıtma


