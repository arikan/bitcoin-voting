[English](#Simple-and-secure-voting-system-with-Bitcoin)
[Türkçe](#Bitcoin-ile-güvenli-ve-basit-bir-oy-sistemi)

# Simple and secure voting system with Bitcoin

A schema designed to utilize Bitcoin cryptocurrency for secure and simple electronic voting. In the heart of the schema lies the Blockchain, so all the processes of the system are open to public audition.

Requirements:

All actors of the election should be able to have a Bitcoin account and should be able to secure their voting computer.

Actors:

Election Authority
Candidate
Voter

Terminology:

Block Chain: Bitcoin public transaction list
0.00000001 Bitcoin: the smallest unit of Bitcoin
BTC: Abbreviation for Bitcoin currency

Schema:

0. Election Authority declaration:
Election Authority publicly announces its Bitcoin address.

1. Voter registration:
Voters show a valid ID and provide their Bitcoin address to Election Authority, who sends them 0.00000001 BTC in return. All voter Bitcoin addresses are publicly listed in the Blockchain. To carry out citizens' right to vote anonymously, the Election Authority keeps the IDs to prevent double registration but does not keep a record of association between the IDs and the provided Bitcoin addresses.

2. Candidate registration:
Candidates provide a valid ID and their Bitcoin address to Election Authority, who sends them 0.00000002 BTC in return. All candidate Bitcoin addresses are publicly listed in the Blockchain. As opposed to voter registration, Election Authority keeps and publicly announces a record of association between each candidate ID and their provided Bitcoin address. Candidates are obliged to announce their Bitcoin addresses.

3. Starting the election:
Election starts when Election Authority sends 0.00000001 BTC to all the voters' Bitcoin addresses publicly listed in the BLockchain.

4. Voting:
Voters send 0.00000001 BTC to their preferred candidate's Bitcoin addresses publicly listed in the Blockchain.

5. Ending the election:
Election ends when all voting transactions are processed for each candidate in the Blockchain. A time limit can be also put in place.

6. Election result:
Election result is obtained by counting all valid voting transactions from the registered voting addresses to the registered candidate addresses in the Blockchain. Any other transaction after the first 0.00000001 BTC transaction from the voter to the candidate is considered disqualified. The whole process from the registrations to the voting and counting the results is open to audition by anyone.

This basic schema can be applied today with the existing Bitcoin infrastructure. One can develop applications and interfaces for better user experience of this system. To contribute and improve the schema please send your comments and questions to the comments section of this page, or feel free to fork the repository and send pull requests.


# Bitcoin ile güvenli ve basit bir oy sistemi

Şifreli elektronik para birimi Bitcoin 2009'da ilk kullanıma girdiğinden beri internet üzerinde çalışan bir değer aktarım katmanı olarak hızla yayılmakta. Alışveriş ve borsalar dışında elektronik noterlik, elektronik sözleşme vb pek çok farklı alanda kullanılmakta.

Aşağıda göreceğiniz Bitcoin ile çalışan bir sistem şemasıdır. Herkese açık ve anonim kayıt tutan Bitcoin işlem defteri Blockchain bu sistemin çekirdeğini oluşturmakta ve aşağıda belirtilen tüm aşamalar isteyen herkesin denetimine açıktır ve Bitcoin doğası gereği tüm işlemler şifrelidir.

Gereksinimler:

Seçime katılacak tüm taraflar birer Bitcoin hesabı açabilmelidir ve oy verecekleri bilgisayarın güvenliğini sağlayabilmelidir.

Aktörler:

Seçim Düzenleyicisi (Örn yüksek seçim kurulu)
Aday (Örn Belediye Başkanı Adayı ya da Siyasi Parti)
Seçmen (Örn oy verebilen vatandaş)

Terimler:

Blockchain: Herkese açık Bitcoin işlem defteri
0.00000001 bitcoin: Mümkün olan en küçük Bitcoin birimi
BTC: Bitcoin para birimi kısaltması

Şema:

0. Seçim Düzenleyicisi'nin ilanı:
Seçim Düzenleyicisi Bitcoin hesap numarasını ilan eder.

1. Seçmen kaydı:
Seçim Düzenleyicisi kimliğini gösterip Bitcoin hesabını ibraz eden her seçmene 0.00000001 BTC gönderir. Böylece seçmenlerin Bitcoin adresleri Blockchain'de listelenmiş olur. Seçmenlerin anonim oy verme hakkını kullanabilmesi için Seçim Düzenleyicisi kayıt aşamasında kaydın bir defa yapıldığını kontrol etmek üzere sadece kimlik bilgisini tutar, Bitcoin hesap numarası kayıt edilmemelidir.

2. Aday kaydı:
Seçim Düzenleyicisi kimliğini ve Bitcoin hesabını ibraz eden her adayın hesabına 0.00000002 BTC gönderir. Böylece adaylar Blockchain'de listelenmiş olur. Seçmen kaydının tersine Seçim Düzenleyicisi Adayları kaydederken kimlik bilgisiyle Bitcoin hesabını eşleştirerek tutmak ve eşleştirmeyi herkese açıklamak zorundadır. Seçim Düzenleyicisi'nin Bitcoin hesabından gönderilen 0.00000002 bitcoini alanlar aday olarak listelenmiş olur. Adaylar Bitcoin hesaplarını ilan etmekle yükümlüdür.

3. Seçimi başlatma:
Seçim Düzenleyicisi listelenmiş tüm seçmenlere tekrar 0.00000001 BTC gönderdiğinde seçim başlar.

4. Oy verme:
Seçmenler listelenen adaylardan birine 0.00000001 BTC gönderdiklerinde oy vermiş olurlar. Bir seçmenin hesabından listelenen Adaylardan birinin hesabına sadece bir defa gönderim yapabilir, ilk gönderim sonrasında yapılacak herhangi bir gönderim geçersiz sayılır.

5. Seçimi bitirme:
Tüm kayıtlı seçmenler oy verdiğinde seçim biter. Ayrıca seçimi bitirmek için zaman sınırı da koyulabilir.

6. Oy dökümü ve sayım:
Herkese açık Bitcoin işlem defteri Blockchain'den tüm seçmenlerin listelenmiş adaylara gönderdiği tüm geçerli gönderimler sayılırak seçim sonucu belirlenir. Seçim süreci başlangıcındaki kayıt aşamasından listelenmeye, oy vermeye, ve sonuçların sayılmasına kadar tümüyle Bitcoin Blockhain'de herkesin denetimine açık olarak kayıt altındadır.

Bu temel sistem mevcut Bitcoin altyapısı ile bugün uygulamaya koyulabilir. Daha kolay kullanımlar için seçime özel uygulamalar ve arayüzler geliştirilebilir. Sistemle ilgili gördüğünüz açıklar ya da iyileştirmeler için lütfen önerilerinizi ve eleştirilerinizi yorumlara gönderiniz. Ayrıca doğrudan repo'dan fork/pull ile değiştirebilir ve katkıda bulunabilirsiniz.

