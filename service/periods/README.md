# Periods Servisi
Periods servisine ilgili url üzerinden erişilecektir.

Service URL: **{baseurl}//metroapi/period**
Service metodu: **GET**

## İstek atarken herhangi bir parametre almamaktadır.

## Servis dönüş data deseni

Parametre | Tip
------------ | ------------
weekdays |  hafta içi tren kalkış bilgi listesi
saturdays |  cumartesileri tren kalkış bilgi listesi
sundays |  pazarları tren kalkış bilgi listesi
start_time |  ilgili periyodun başlangıç zamanı
finish_time |  ilgili periyodun bitiş zamanı
frequency | tren kalkış sıklığı (dakika)
