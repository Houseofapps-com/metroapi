# Passengers Servisi
Passengers servisine ilgili url üzerinden erişilecektir.

Service URL: **http://api.izmirhackathon.com/passengers**
Service metodu: **GET**

## İstek atarken herhangi bir parametre almamaktadır.

## Servis dönüş data deseni

Parametre | Tip
------------ | ------------
name |  tren hat isim bilgisi
passenger_information |  yolcu bilgileri listesi
time_start | yolcu sayısı ölçümünün başlandığı saat bilgisi
time_finish | yolcu sayısı ölçümünün sonlandığı saat bilgisi
total_passenger | ilgili saat aralığında tüm istasyonlardaki toplam yolcu sayısı
passengerByStation | İlgili saat aralığında istasyon bazlı yolcu sayı bilgi listesi
station_id | istasyon id bilgisi
station_name | istasyon isim bilgisi
passenger_count | ilgili saat aralığında istasyondaki yolcu sayı bilgisi