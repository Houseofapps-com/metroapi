# Parking Servisi
Parking servisine ilgili url üzerinden erişilecektir.

Service URL: **{baseurl}//metroapi/parking**
Service metodu: **GET**

## İstek atarken herhangi bir parametre almamaktadır.

## Servis dönüş data deseni

Parametre | Tip
------------ | ------------
parkId |  otopark id bilgisi
name |  otopark adı
type | otopark tip bilgisi
status | otopark durum bilgisi
occupancy | doluluk oran bilgisi listesi
free | boş slot bilgisi
occupied | dolu slot bilgisi
openingHours | Çalışma saat bilgileri
isPaid | Ücretli - ücretsiz otopark bilgisi ( boolean)
accessibility | Otopark erişebilirlik bilgi listesi
disable | Engelli otopark yeri bilgisi (boolean)
lpgAllowed | LPG li araç park bilgisi ( boolean)
payment | Otopark ödeme türü bilgi listesi 
sms | sms ile ödeme bilgisi ( boolean)
card | kredi kartı - debit kart ödeme bilgisi ( boolean)
cash | nakit ödeme bilgisi ( boolean)
poi | ilgili otoparka toplu taşıma araç yakınlık bilgi listesi
metroStation | otoparkın metro istasyonuna yakınlık bilgisi (boolean)
tramStation | otoparkın tramvay istasyonuna yakınlık bilgisi ( boolean)
trainStation | otoparkın tren istasyonuna yakınlık bilgisi ( boolean)
busStation | otoparkın otobüs durağına yakınlık bilgisi ( boolean)
lat | ilgili otopark enlem bilgisi
long | ilgili otopark boylam bilgisi 

