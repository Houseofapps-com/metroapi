# Locations Servisi
Locations servisine ilgili url üzerinden erişilecektir.

Service URL: **http://api.izmirhackathon.com/locations**
Service metodu: **GET**

## İstek atarken herhangi bir parametre almamaktadır.

## Özel olarak tek bir istasyon bilgisine erişilmek istenirse parametre olarak ilgili url sonuna istasyon id si eklenerek istek atılmalıdır.

Örnek URL: **http://api.izmirhackathon.com/locations?id=1**

## Servis dönüş data deseni

Parametre | Tip
------------ | ------------
id |  istasyon id bilgisi
station |  istasyon adı
lat | ilgili istasyon enlem bilgisi
long | ilgili istasyon boylam bilgisi 
station_type | ilgili istasyon tipi
tramway | tramvaya aktarma var-yok bilgisi (boolean)
izban | izbana aktarma var-yok bilgisi(boolean)
