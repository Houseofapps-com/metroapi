# İzmir Hackathon 2020 Resmi Uygulama Geliştirme Arayüz Dökümanı.
* Resmi olarak hackathon süresince kullanılacak BASEURL: **http://api.izmirhackathon.com**
* Döküman içerisinde geçen parametreler ve desteklenen data yapıları tamamen mevcut uygulama ara katmanı ile aynı versiyondadır. **Parametreler** ve **Servis Ucu** uyumluluklarına dikkat edilmelidir.
* Servis uçlarının kullanımlarında hangi http metodları ile gelinmesi istendiğine dikkat edilmelidir. Uygulama ara katmanı genel **get** ve **post** metodları ile calışmaktadır.

Modul | Aciklama
------------ | ------------
[Mesafeler](service/distance/README.md) | Mesafe bilgileri üzerine detaylar.
[Lokasyonlar](service/locations/README.md) | İstasyon kordinatlari üzerine detaylar.
[Periyotlar](service/periods/README.md) | Periyotlar üzerine detaylar.
[Istasyonlar](service/stations/README.md) | İstasyonlar üzerine detaylar.
[Otoparklar](service/parking/README.md) | Otoparklar üzerine detaylar.
[Yolcular](service/passenger/README.md) | Yolcular üzerine detaylar.