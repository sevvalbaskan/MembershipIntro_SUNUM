# MembershipIntro_SUNUM
Merhaba, MembershipIntro İstanbul - Beşiktaş Wissen Akademi'de Eğitmenlik yaptığım süreçte 302 sınıfım ile yazdık.Bu projedeki amaç üyelik sistemlerini yakınsamaktır.Bu proje ile amacımız gerçek hayata yaklaşmak ve istihdam sürecindeki hazır bulunuşluğu maksimum seviyeye getirebilmektir.

 Burada projenin ekran resimlerini ve kaynak kodlardan bazı kod parçalarını aşağıda görebilirsiniz.

PROJE HAKKINDA TEKNİK BİLGİLER:

* Proje Visual Studio .Net 6 ASP.NET MVC CORE ile yazıldı.
*Proje Entity Framework Core Code-First yaklaşımıyla yazılmıştır.
*Projede üye olurken üyelerin şifreleri System.Security.Cryptography-SHA512 ile hash-salt yapısıyla gizlenerek kayıt edilmiştir.
*Şifremi unuttum butonu ile üyeye email gönderilerek şifresini yenilemesi sağlanır.
*Projeyi 4 katman (EL,DAL,BLL,UI) olarak yazdık.
*Projede Kayıt Ol, Giriş Yap, Telefon Ekle, Telefon Sil sayfaları bulunmaktadır. Üye sisteme giriş yaptıktan sonra aşağıdaki adımları izleyerek telefon ekleyebilir.
*Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir.
*Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz.

![image](https://user-images.githubusercontent.com/73429501/220879007-00d97d14-bec6-4645-9190-665df2bd4f62.png)
![Membership3](https://user-images.githubusercontent.com/73429501/220879054-1d025044-7f46-4dd7-83be-f77449604ee2.JPG)
Buradan kayıt oluşturuyoruz. Telefon tipi yoksa ekleyebilir ya da var olan tipte farklı bir telefon numarası yazabiliriz.
![Membership5](https://user-images.githubusercontent.com/73429501/220879375-32c8e314-d905-4e4d-a8d8-a87b82d70180.JPG)

Daha önce kaydettiğimiz kayıtlar burda listelenir.
![image](https://user-images.githubusercontent.com/73429501/220879210-ff4cb6d9-51d2-481e-b3dd-35ef196b3d96.png)


