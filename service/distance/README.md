# Distance Servisi
Distance servisine ilgili url uzerinden erisilecektir.

Service URL: **{baseurl}//metroapi/distance**
Service metodu: **GET**

## Istek atarken herhangi bir parametre almaktadir.

## Servis donus data deseni

Parametre | Tip
------------ | ------------
id_st | baslangic istasyon id bilgisi
station_start | baslangic istasyon adi
id_end | bitis istasyon id bilgisi
station_end | bitis istasyon adi 
distance(mt) | integer tipli mesafe bilgisi (metre)
duration(sec) | integer tipli sure bilgisi (saniye)
wait(sec) | integer tipli istasyonda bekleme suresi (saniye)
travel(sec) | integer tipli toplam seyahat suresi (saniye)

