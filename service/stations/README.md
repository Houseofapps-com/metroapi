# Stations Servisi
Stations servisine ilgili url üzerinden erişilecektir.

Service URL: **http://api.izmirhackathon.com/stations**
Service metodu: **GET**

## İstek atarken herhangi bir parametre almamaktadır.

## Özel olarak tek bir istasyon bilgisine erişilmek istenirse parametre olarak ilgili url sonuna istasyon id si eklenerek istek atılmalıdır.

Örnek URL: **http://api.izmirhackathon.com/stations?id=1**
## Servis dönüş data deseni

Parametre | Tip
------------ | ------------
station |  istasyon adı
line | integer tipli ilgili istasyondaki ray sayısı
escalator | integer tipli ilgili istasyondaki yürüyen merdiven sayısı 
elevator | integer tipli ilgili istasyondaki asansör sayısı
is_peron_ada | istasyon ada tipi bilgisi(booelan)
ticket_office | integer tipli ilgili istasyondaki bilet ofis sayısı
toll_gate_ent | integer tipli ilgili istasyondaki giriş turnike sayısı
toll_gate_ex | integer tipli ilgili istasyondaki çıkış turnike sayısı
entrance_exit | integer tipli ilgili istasyondaki giriş-çıkış sayısı

