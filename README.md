Projeyi çalıştırmadan önce "npm install" ile node-modules dosyasını indiriniz.

CV hazırlama ve görüntüleme projesi 

1. Ekran : Login  ( Kullanıcı Girişi,Yönetici Girişi )
2. Ekran CV bilgilerinin girişi ve güncellenmesi (Kullanıcı Rolü için)
	CV de yer alacak bilgiler : 
•	Ad  soyad 
•	Cep numarası 
•	email 
•	Eğitim bilgileri (Okul - Dönem ) 
•	iş tecrübesi (İş yeri - yıl - açıklama ) 
•	Mesleki Beceri ve bilgileri 
	
3. Kaydedilen cv bilgilerinin listelenebileceği ekran ( Yönetici Rolü için ) 					
	Liste ekranında ad soyad email ve cep no görüntülenecek . Listede ilgili 
    adayın satırını seçince CV nin detaylarının görebileceğimiz bir ekran.

Kullanılacak teknojiler : önyüz react , backendde java spring kullanılacak . Veri tabanı mysql . 

-------------------------------------------------

+ ilk girişte kullanıcı veya yönetici olduğu seçilmelidir.
	+ eğer yönetici ise kayıt kısmı aktif olmayacaktır sadece kullanıcılar kayıt olabilirler.
+ kullancı girişinde daha önce cv oluşturduysa cv güncelleme butonu,
	+ henüz kayıt olmadıysa cv oluşturma butonu aktif olacaktır.
+ yönetici girişinde tüm kullanıcıların oluşturmuş olduğu cv'ler görüntülenir. 
	+ detay istenen kullanıcının detay butonuna basılarak tüm bilgilere ulaşılabilir.
