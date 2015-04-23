[English](#simple-and-secure-voting-system-with-bitcoin) ∙ [Türkçe](#bitcoin-ile-g%C3%BCvenli-ve-basit-bir-oy-sistemi) ∙ [Bahasa Malaysia](#sistem-pengundian-selamat-dan-mudah-dengan-bitcoin)

## Simple and secure voting system with Bitcoin

A schema designed to utilize Bitcoin cryptocurrency for secure and simple electronic voting. In the heart of the schema lies the Blockchain, so all the processes of the system are open to public audition.

#### Requirements:

* All actors of the election should be able to have a Bitcoin account.
* All actors of the election should be able to secure their voting computer.

#### Actors:

* Election Authority
* Candidate
* Voter

#### Terminology:

* Block Chain: Bitcoin public transaction list
* 0.00000001 Bitcoin: the smallest unit of Bitcoin
* BTC: Abbreviation for Bitcoin currency

#### Schema:

0. **Election Authority declaration:**
Election Authority publicly announces its Bitcoin address.

1. **Voter registration:**
Voters show a valid ID and provide their Bitcoin address to Election Authority, who sends them 0.00000001 BTC in return. All voter Bitcoin addresses are publicly listed in the Blockchain. To carry out citizens' right to vote anonymously, the Election Authority keeps the IDs to prevent double registration but does not keep a record of association between the IDs and the provided Bitcoin addresses.

2. **Candidate registration:**
Candidates provide a valid ID and their Bitcoin address to Election Authority, who sends them 0.00000002 BTC in return. All candidate Bitcoin addresses are publicly listed in the Blockchain. As opposed to voter registration, Election Authority keeps and publicly announces a record of association between each candidate ID and their provided Bitcoin address. Candidates are obliged to announce their Bitcoin addresses.

3. **Starting the election:**
Election starts when Election Authority sends 0.00000001 BTC to all the voters' Bitcoin addresses publicly listed in the BLockchain.

4. **Voting:**
Voters send 0.00000001 BTC to their preferred candidate's Bitcoin addresses publicly listed in the Blockchain.

5. **Ending the election:**
Election ends when all voting transactions are processed for each candidate in the Blockchain. A time limit can be also put in place.

6. **Election result:**
Election result is obtained by counting all valid voting transactions from the registered voting addresses to the registered candidate addresses in the Blockchain. Any other transaction after the first 0.00000001 BTC transaction from the voter to the candidate is considered disqualified. The whole process from the registrations to the voting and counting the results is open to audition by anyone.

#### Contribution

This basic schema can be implemented today with the existing Bitcoin infrastructure. One can develop applications and interfaces for better user experience of this system. Please send your comments and questions on issues and feel free to fork the repository and send pull requests.

#### License

[The MIT License (MIT)](https://github.com/arikan/bitcoin-voting/blob/master/LICENSE)


## Bitcoin ile güvenli ve basit bir oy sistemi

Şifreli elektronik para birimi Bitcoin 2009'da ilk kullanıma girdiğinden beri internet üzerinde çalışan bir değer aktarım katmanı olarak hızla yayılmakta. Alışveriş ve borsalar dışında elektronik noterlik, elektronik sözleşme vb pek çok farklı alanda kullanılmakta.

Aşağıda göreceğiniz Bitcoin ile çalışan bir sistem şemasıdır. Herkese açık ve anonim kayıt tutan Bitcoin işlem defteri Blockchain bu sistemin çekirdeğini oluşturmakta ve aşağıda belirtilen tüm aşamalar isteyen herkesin denetimine açıktır ve Bitcoin doğası gereği tüm işlemler şifrelidir.

#### Gereksinimler:

* Seçime katılacak tüm taraflar birer Bitcoin hesabı açabilmelidir.
* Seçime katılacak tüm taraflar oy verecekleri bilgisayarın güvenliğini sağlayabilmelidir.

#### Aktörler:

* Seçim Düzenleyicisi (Örn yüksek seçim kurulu)
* Aday (Örn Belediye Başkanı Adayı ya da Siyasi Parti)
* Seçmen (Örn oy verebilen vatandaş)

#### Terimler:

* Blockchain: Herkese açık Bitcoin işlem defteri
* 0.00000001 bitcoin: Mümkün olan en küçük Bitcoin birimi
* BTC: Bitcoin para birimi kısaltması

#### Şema:

0. **Seçim Düzenleyicisi'nin ilanı:**
Seçim Düzenleyicisi Bitcoin hesap numarasını ilan eder.

1. **Seçmen kaydı:**
Seçim Düzenleyicisi kimliğini gösterip Bitcoin hesabını ibraz eden her seçmene 0.00000001 BTC gönderir. Böylece seçmenlerin Bitcoin adresleri Blockchain'de listelenmiş olur. Seçmenlerin anonim oy verme hakkını kullanabilmesi için Seçim Düzenleyicisi kayıt aşamasında kaydın bir defa yapıldığını kontrol etmek üzere sadece kimlik bilgisini tutar, Bitcoin hesap numarası kayıt edilmemelidir.

2. **Aday kaydı:**
Seçim Düzenleyicisi kimliğini ve Bitcoin hesabını ibraz eden her adayın hesabına 0.00000002 BTC gönderir. Böylece adaylar Blockchain'de listelenmiş olur. Seçmen kaydının tersine Seçim Düzenleyicisi Adayları kaydederken kimlik bilgisiyle Bitcoin hesabını eşleştirerek tutmak ve eşleştirmeyi herkese açıklamak zorundadır. Seçim Düzenleyicisi'nin Bitcoin hesabından gönderilen 0.00000002 bitcoini alanlar aday olarak listelenmiş olur. Adaylar Bitcoin hesaplarını ilan etmekle yükümlüdür.

3. **Seçimi başlatma:**
Seçim Düzenleyicisi listelenmiş tüm seçmenlere tekrar 0.00000001 BTC gönderdiğinde seçim başlar.

4. **Oy verme:**
Seçmenler listelenen adaylardan birine 0.00000001 BTC gönderdiklerinde oy vermiş olurlar. Bir seçmenin hesabından listelenen Adaylardan birinin hesabına sadece bir defa gönderim yapabilir, ilk gönderim sonrasında yapılacak herhangi bir gönderim geçersiz sayılır.

5. **Seçimi bitirme:**
Tüm kayıtlı seçmenler oy verdiğinde seçim biter. Ayrıca seçimi bitirmek için zaman sınırı da koyulabilir.

6. **Oy dökümü ve sayım:**
Herkese açık Bitcoin işlem defteri Blockchain'den tüm seçmenlerin listelenmiş adaylara gönderdiği tüm geçerli gönderimler sayılırak seçim sonucu belirlenir. Seçim süreci başlangıcındaki kayıt aşamasından listelenmeye, oy vermeye, ve sonuçların sayılmasına kadar tümüyle Bitcoin Blockhain'de herkesin denetimine açık olarak kayıt altındadır.

#### Katılım

Bu temel sistem mevcut Bitcoin altyapısı ile bugün uygulamaya koyulabilir. Daha kolay kullanımlar için seçime özel uygulamalar ve arayüzler geliştirilebilir. Sistemle ilgili gördüğünüz açıklar ve iyileştirmeler için lütfen önerilerinizi ve eleştirilerinizi gönderiniz. Ayrıca doğrudan repo'dan fork/pull ile değiştirebilir ve katkıda bulunabilirsiniz.

#### Lisans

[The MIT License (MIT)](https://github.com/arikan/bitcoin-voting/blob/master/LICENSE)

## Sistem pengundian selamat dan mudah dengan Bitcoin

Kaedah kerja menggunakan matawang kripto Bitcoin sebagai sistem pengundian yang selamat dan mudah. Di dalam kaedah ini juga menggunakan algoritma Blockchain agar semua proses adalah terbuka kepada semua Rakyat.

#### Keperluan:

* Kesemua aktor pengundian harus mempunyai satu akaun Bitcoin (wallet).
* Kesemua aktor pengundian harus menggunakan komputer untuk mengundi.

#### Aktor:

* Pihak Berkuasa Pengundian (SPR)
* Calon
* Pengundi (Rakyat)

#### Terminologi:

* Block Chain: Senarai awam transaksi Bitcoin
* 1 Satoshi (0.00000001 Bitcoin): Unit terkecil matawang Bitcoin
* BTC: Singkatan matawang Bitcoin

#### Skema:

1. **Pendaftaran pengundi:**
 - Pengundi menyediakan ID dan alamat Bitcoin yang sah kepada Pihak Berkuasa Pengundian, seterusnya menyalurkan 1 Satoshi kepada pengundi tersebut.
 - Semua alamat Bitcoin calon akan dipaparkan secara terbuka di dalam Blockchain.
 - Untuk mengekalkan privasi pengundi, Pihak Berkuasa Pengundian menyimpan ID untuk mengelakkan pendaftaran berganda, tetapi tidak menyimpan rekod yang berkaitan dengan ID dan alamat Bitcoin yang diberikan.

2. **Pendaftaran calon:**
- Calon menyediakan ID dan alamat Bitcoin yang sah kepada Pihak Berkuasa Pengundian, seterusnya menyalurkan 2 Satoshi kepada calon tersebut.
- Semua alamat Bitcoin calon akan dipaparkan secara terbuka di dalam Blockchain.
- Dalam hal calon, Pihak Berkuasa Pengundian akan menyimpan rekod berkaitan ID dan alamat Bitcoin calon, dan berkuasa untuk memaparkan kedua-duanya secara terbuka.
- Calon calon wajib mengumumkan alamat Bitcoin mereka.

3. **Pilihan raya:**
- Pilihan raya bermula apabila Pihak Berkuasa Pengundian menyalurkan 1 Satoshi kepada semua alamat Bitcoin pengundi.
- Alamat Bitcoin pengundi boleh disemak di Blockchain.

4. **Pengundian:**
- Pengundi akan melakukan pemindahan/transaksi 1 Satoshi kepada alamat Bitcoin calon yang dipilih.
- Proses transaksi Satoshi boleh disemak di Blockchain.

5. **Pengakhiran proses pengundian:**
- Proses pengundian akan berakhir apabila semua transaksi telah diproses dan disahkan oleh Pihak Berkuasa Pengundian.
- Had masa juga boleh di gunakan dalam proses ini.

6. **Election result:**
- Keputusan pengundian diputuskan dengan mengira semua transaksi yang sah daripada alamat pengundian menggunakan Blockchain API.
- Semua proses-proses di atas daripada proses pendaftaran adalah terbuka kepada semua Rakyat.

#### Todo
- Ikut proses sebenar PRU Malaysia
- Cari isu berbangkit dalam kaedah ini

#### Sumbangan:

- Kaedah asas ini boleh dilaksanakan menggunakan infrastruktur Bitcoin yang sedia ada.
- Sumbangan kepada teknologi boleh dilakukan dengan membina sebuah aplikasi sistem antara muka untuk pengalaman pengguna yang baik.
- Anda boleh menyumbang dengan memberi pendapat dan soalan berkaitan isu-isu berbangkit.
- Adalah digalakkan untuk fork repositori dan hantar pull request.


#### Lesen

[The MIT License (MIT)](https://github.com/arikan/bitcoin-voting/blob/master/LICENSE)