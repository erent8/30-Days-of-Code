HTTP (Hypertext Transfer Protocol), web tarayıcıları ve web sunucuları arasında veri iletişimini sağlayan bir protokoldür. İnternet üzerinden bilgi alışverişi için kullanılan standart yöntemdir.

#### HTTP'nin temel çalışma prensibi istek-yanıt modelidir:

- İstek (Request): Bir kullanıcı web tarayıcısında bir sayfayı açmak istediğinde, tarayıcı sunucuya bir HTTP isteği gönderir.
- Yanıt (Response): Sunucu bu isteği alır, işler ve uygun bir HTTP yanıtı ile cevap verir.

Örnek:
Diyelim ki bir kullanıcı tarayıcısına ``` "www.ornek.com"``` yazıp Enter'a bastı.

İstek:

```
GET / HTTP/1.1
Host: www.ornek.com
```
Bu istek, ```"www.ornek.com" ``` sunucusundan ana sayfayı (/) talep ediyor.

Yanıt:
```
HTTP/1.1 200 OK
Content-Type: text/html

<!DOCTYPE html>
<html>
<head>
    <title>Örnek Sayfa</title>
</head>
<body>
    <h1>Merhaba Dünya!</h1>
</body>
</html>
```
Bu yanıt, isteğin başarılı olduğunu (200 OK) ve HTML içeriğini döndürüyor.
HTTP, web sayfalarının yanı sıra resimler, videolar, API çağrıları gibi çeşitli veri türlerinin iletimi için de kullanılır. GET, POST, PUT, DELETE gibi farklı istek metodları ile çeşitli işlemler gerçekleştirilebilir.
