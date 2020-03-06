# Distance Servisi
Distance servisine ilgili url üzerinden erişilecektir.

Service URL: **http://api.izmirhackathon.com/distance**
Service metodu: **GET**

## İstek atarken herhangi bir parametre almamaktadır.

## Servis dönüş data deseni

Parametre | Tip
------------ | ------------
id_st | başlangıç istasyon id bilgisi
station_start | başlangıç istasyon adi
id_end | bitiş istasyon id bilgisi
station_end | bitiş istasyon adi 
distance(mt) | integer tipli mesafe bilgisi (metre)
duration(sec) | integer tipli süre bilgisi (saniye)
wait(sec) | integer tipli istasyonda trenin bekleme süresi (saniye)
travel(sec) | integer tipli toplam seyahat süresi (saniye)

