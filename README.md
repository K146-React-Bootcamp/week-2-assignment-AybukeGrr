# HTTP Status Kodları
HTTP durum kodları, bir web sayfasının barındırıldığı sunucuya, istemciden gönderilen HTTP isteğine yanıt olarak döndürülen kodlara verilen isimdir.

## HTTP Status Kodu Sınıfları
### 1xx: 
Tarayıcı tarafından gönderilen isteğin sunucuya ulaştığını ve işlemin başladığını bildiren bilgilendirme kodlarını ifade eden durum kodlarıdır.

### 2xx:
Tarayıcı tarafından gönderilen isteğin sunucuya ulaştığını, anlaşıldığını ve başarılı olduğunu ifade eden durum kodlarıdır.

### 3xx: 
Erişilmek istenen kaynağın başka bir kaynağa taşındığını ve bir yönlendirmenin söz konusu olduğunu ifade eden durum kodlarıdır.

### 4xx:
İsteğin yerine getirilemediğini, ilgili web sayfasına ya da web sitesine ulaşılamadığını ifade eden durum kodlarıdır.

### 5xx:
Tarayıcı tarafından gönderilen isteğin başarıyla sunucuya ulaştığını fakat sunucu tarafındaki sorunlar nedeniyle isteğin yerine getirilemediğini ifade eden durum kodlarıdır.

## En Sık Karşılaşılan Durum Kodları
### 200 Durum Kodu (Başarılı)

![This is an image](https://armyyazilim.com/wp-content/uploads/2019/10/http-200.png)

En kısa tanımıyla ideal durum kodudur. Bir web sayfası sorunsuz şekilde açılıyorsa sunucudan tarayıcıya 200 durum kodu gönderilir. Sunucudan tarayıcıya 200 durum kodu iletiliyorsa ziyaretçi ve web sitesi için her şey olması gerektiği gibidir diyebiliriz.

### 301 Durum Kodu (Kalıcı Yönlendirme)

![This is an image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbjcB3q96w0bdczmcpWU1cOGUTDfGRjp53Ap5NdvhhKasJ9Mig6gqL4kRDMDQoQ36062c&usqp=CAU)

Bir web sayfasının kalıcı olarak bir başka web sayfasına yönlendirildiği ve sayfayı ziyaret eden kullanıcının da otomatik olarak yönlenmesini sağlayan durum kodudur. 301 durum kodu kullanılarak yönlendirilen sayfalar içerik bakımından çok benzer ya da alakalı olduğunda güç kaybı en aza indirilebilir. Bu nedenle web sitesi taşıma gibi işlemlerde kullanılması önerilen en önemli durum kodlarından biridir.

### 302 Durum Kodu (Geçici Yönlendirme)

![This is an image](https://lh6.googleusercontent.com/YkNPa5247DAYmcnA8djAGb-NUjH5hezEEbtQXhU0L4dIYWhuP-m2Or8eIrGrSxQrOncKEw8pv7YoEVOMq8-7OaDCby02pN5G-cz3r7TGS1ovb1blz4K4I-cdnMhD5Lun5BgVg40v)

Bir web sayfasının geçici olarak bir başka web sayfasına yönlendirildiğini ifade eden durum kodudur. 301 yönlendirme kodundan farkı ilgili sayfanın test aşamasında olması, bakıma alınması ya da bir e-ticaret sitesi için ilgili ürünün stoklarının geçici olarak tükenmesi gibi ilgili sayfanın tekrar aktif edileceği durumlarda kullanılmasıdır. Fakat kullanıcılar 301 yönlendirmesi ile 302 yönlendirmesi arasındaki farkı anlamayacaktır. İlgili sayfaya giriş yapan kullanıcılar direkt olarak diğer sayfaya yönlendirilecektir.

### 403 Durum Kodu (Erişim İzni Sorunu)

![This is an image](https://i.insider.com/605a704f106eb50019d053e0?width=750&format=jpeg&auto=webp)

Kullanıcının bir web sayfasına erişmek adına sunucuya gönderdiği isteğe karşılık ilgili web sayfasına erişim izni olmadığı ya da ilgili web sayfasının yasaklandığını ifade eden durum kodudur.

### 404 Durum Kodu (Bulunamadı)

![This is an image](https://www.ticimax.com/Uploads/images/http-durum-kodlari-ve-anlamlari-404-05f776.jpg)

Kullanıcının görüntülemek istediği web sayfasının ilgili sunucuda bulunmadığını ifade eden durum kodudur. İlgili web sayfası silinmiş ya da URL’si değiştirilmiş olabilir. Fakat 404 durum kodları ilgili sayfanın geçici ya da kalıcı olarak ulaşılamadığı hakkında bir fikir vermez. Kullanıcılar ulaşmak istedikleri bir web sayfasında 404 durum kodu ile karşılaştıklarında genelde siteyi terk ederek farklı web sitelerine yönelirler. Özellikle çok trafik alan ya da URL’i kullanıcılar tarafından bilinen bir sayfa ise bu durum ilgili web sitesini kötü etkileyecektir. Bu nedenle 404 durum kodu içeren sayfaların alakalı karşılıkları varsa yönlendirilmesi önerilir.

Fakat ilgili web sayfası bir süre sonra tekrar aktif olacak ya da bir e-ticaret sitesi için ilgili ürün tekrar stoklarda yer alacaksa ilgili sayfanın 404 durum kodu içerecek şekilde kalması daha doğru olacaktır. 404 şeklinde bırakılan web sayfalarındaki kullanıcıları kaybetmeyip farklı sayfalara yönlendirerek web sitesi içerisinde tutmaya çalışmalıyız. Bu nedenle özel olarak tasarlanan custom 404 sayfaları ile kullanıcıların web sitesini terk etmek yerine farklı sayfalara yönelmelerine yardımcı olabiliriz.

### 410 Durum Kodu (Kalıcı Olarak Bulunmuyor)

![This is an image](https://i.ytimg.com/vi/JqLz0ULmGUY/maxresdefault.jpg)

Kullanıcının erişmek istediği web sayfasının sunucuda bulunmadığını ifade eden durum kodudur. 404 durum kodundan farkı ilgili web sayfasının kesin ve kalıcı olarak silindiğini ve geri gelmeyeceğini ifade etmektedir. Ayrıca arama motoru botları 410 durum kodu içeren web sayfaları ile karşılaştığında arama motorları ilgili sayfayı dizinden daha hızlı çıkarabilir. Bu nedenle kullanılırken oldukça dikkate edilmesi gereken durum kodlarından biridir.

### 500 Durum Kodu (Sunucu Hatası)

![This is an image](https://www.e-ticaretsitesi.com/wp-content/uploads/2022/08/http-500-hata-kodu.jpg)

Sunucu kaynaklı problemlerde karşılaşılan durum kodudur. Sunucuda bir şeylerin ters gittiğini ifade etmektedir. 500 durum kodu içeren web siteleri için ilgili sunucu probleminin en kısa sürede çözülmesi gerekir. Çünkü arama motorları kullanıcıların ya da arama motoru botlarının erişemediği web sitelerini kullanıcılarına sunmak istemeyecektir.

### 503 Durum Kodu (Sunucu Kullanılamıyor)

![This is an image](https://www.wpoven.com/blog/wp-content/uploads/2020/04/503-image1.jpg)

Sunucu tarafında geçici bir sorun olduğunu ifade eden durum kodudur. Genelde sunucuların bakımda olduğu ya da aşırı yüklenme sonucu geçici olarak devre dışı kaldığı durumlarda karşılaşılır. Örneğin üniversite sınavı sonuçları açıklandığında ÖSYM sitesinin ya da büyük bir indirimde ilgili web sitesine geçici süreyle ulaşılamaması bu duruma örnek olarak gösterilebilir. Ayrıca kötü niyetli kişiler tarafından bant genişliğine yönelik yapılan saldırılarda da sunucu geçici olarak devre dışı kalacak ve kullanıcılar ilgili web sitesine giriş yapmak istediklerinde 503 durum kodu ile karşılaşacaktır.


# HTTP Request Metodları
HTTP ya da uzun uzun Hypertext Transfer Protocol istemci ile host için ihtiyaç duyulan protokolleri sağlar. Bu protokoller bilgiye nasıl erişileceğini, bilginin nasıl transfer edileceğini, gösterileceğini ve belirli bir komut geldiğinde nasıl hareket edileceğini belirler.

### 1. GET: 
Get Metodu sunucudaki kaynaklara erişmek için kullanılır. GET metodu ile URL üzerinden verileri gönderilebilir. Avantjlı yanı; URL üzerinden veriler arasında gezinilebilir, veriler üzerinde değişiklik yapılıp tekrar gönderebilir, hatta “geri” tuşuna basılarak önceki sorgular tekrar gönderilebilir.
URL’lerin ekranda görüntüleniyor olması güvenlik açısından problem yaratmaktadır. Bu yüzden hassas bilgiler GET ile gönderilmemelidir.

![This is an image](https://blog.kakaocdn.net/dn/kHOj6/btqydQELTLd/F8eugrrqVzNEaebLkn1AhK/img.jpg)

### 2. POST: 
Bu metod ile sunucuya veri yazdırabiliriz. Bu metodla istek parametreleri hem URL içinde hem de mesaj gövdesinde gönderilebilir. Sadece mesaj gövdesinin kullanımı yukarıda sayılan riskleri engelleyecektir.Tarayıcılar geri butonuna basıldığında POST isteğinin mesaj gövdesinde yer alan parametreleri tekrar göndermek isteyip istemediğimizi sorarlar. Bunun temel nedeni bir işlemi yanlışlıkla birden fazla yapmayı engellemektir. Bu özellik ve de güvenlik gerekçeleriyle bir işlem gerçekleştirileceğinde POST metodunun kullanılması önerilir.

### 3. PUT: 
Bu metodu kullanarak servis sağlayıcı üzerindeki kaynağı (kaynağın ID’sini göndermek şartıyla) güncelleyebilirsiniz veya yeni bir kaynak oluşturabilirsiniz.

### 4. HEAD: 
Bu metod, servis sağlayıcısı hakkında bilgi almak için kullanılabilir. GET metoduna benzer, fakat bu metodu kullanarak istek yaptığımız zaman dönen cevapta mesaj gövdesi bulunmaz.

### 5. DELETE: 
Bu metod ile sunucu üzerindeki herhangi bir veri silinebilir. Bu sebeple, delete metodunun kullanılabilir olması güvenlik açısından problem oluşturabilir.

### 6. OPTIONS: 
Bu metod, iletişim kurmuş olduğumuz bir kaynağın, kullanılabilecek http metodlarını sunucudan sorgulamak ve kaynağın iletim seçeneklerini tanımlamak için kullanılır.

### 7. TRACE: 
Sunucuya gönderilen isteğin istemciden sunucuya ulaşana kadar uğradığı tüm noktaları ve eğer sunucu ile istemci arasında bir vekil sunucu varsa bu sunucunun ve istek üzerinde yapılan değişikliklerin tespitini sağlamak için kullanılır.

### 8. PATCH: 
Bu metod kısmi kaynakları güncellemek için kullanılabilir. Örneğin, kaynağın yalnızca bir alanını güncellemeniz gerektiğinde, PUT yöntemiyle eksiksiz bir kaynak gösterimi göndermek yavaş olabilir ve daha fazla bant genişliği kullanır.

### 9. SEARCH: 
Bir dizinin altındaki kaynakları sorgulamak için kullanılır.


# FETCH API
Javascript Fetch API, web tarayıcılarından sunuculara HTTP istekleri yapmanızı sağlayan modern bir arayüzdür. FETC API basit ve temizdir. Web tarayıcılarından sunuculara istekte bulunmak için daha esnek özellikler sunmaktadır.

fetch()yöntemi, web tarayıcılarına bir URL’ye istek gönderme talimatı veren global kapsamda mevcuttur.

![This is an image](https://webolog.net/wp-content/uploads/2021/12/javascript-fetch-api.png)

### İstek Gönderme: 
fetch() getirmek istediğiniz kaynağın URL’si olan yalnızca bir parametre gerektirir:

`let response = fetch(url);`

fetch() yöntemi bir Promise döndürür. Böylece then() ve catch() kullanabilirsiniz.

`fetch(url)
    .then(response => {
        // handle the response
    })
    .catch(error => {
        // handle the error
    });`

İstek tamamlandığında kaynak kullanılabilir hale gelir. Şu anda, Promise bir Response nesnesine dönüşecektir.
Response nesnesi, alınan kaynağın API sarmalayıcısıdır. Response nesnesi, yanıtı incelemek için bir dizi faydalı özelliğe ve yönteme sahiptir.

### Yanıtı Okumak: 
Yanıtın içeriği ham metin biçimindeyse, text() yöntemini kullanabilirsiniz. text() yöntemi, alınan kaynağın tüm içeriğiyle çözümlenen bir Promise döndürür:

`fetch(url)
    .then(response => {
fetch('/readme.txt')
    .then(response => response.text())
    .then(data => console.log(data));`

Pratikte, genellikle async/await’i fetch() yöntemiyle şu şekilde kullanırsınız:

`async function fetchText() {
    let response = await fetch('/readme.txt');
    let data = await response.text();
    console.log(data);
}`

text() yönteminin yanı sıra Response nesnesi, ilgili veri türünü işlemek için json(), blob(), formData() ve arrayBuffer() gibi başka yöntemlere sahiptir.

### Yanıtın Durum Kodlarını İşleme:
Response nesnesi, status ve statusText özellikleri aracılığıyla durum kodunu ve durum metnini sağlar. Bir istek başarılı olduğunda durum kodu 200‘dür ve durum metni OK‘dur.
    
    `let response = await fetch('/readme.txt');
    
    let data = await response.text();
   
    console.log(data);


    
    let response = await fetch('/readme.txt');

    console.log(response.status); // 200
    console.log(response.statusText); // OK

    if (response.status === 200) {
        let data = await response.text();
        // handle data`

İstenen kaynak mevcut değilse, yanıt kodu 404‘tür.

` let response = await fetch('/non-existence.txt');

console.log(response.status); // 400

console.log(response.statusText); // Not Found `

fetch(), web tarayıcısı zaman aşımı, ağ bağlantısı kaybı ve CORS ihlali gibi gerçek bir hata oluştuğunda reddeden bir Promise verir.
