## Thunk Sepeti

Küçük bir e-ticaret sitesini andıran bu proje, kullanıcıların ürünleri adetleriyle birlikte sepete eklemelerine, sepetteki ürünleri ise arttırma, azaltma veya çıkarma işlemlerine olanak sağlıyor.

# Redux Thunk

Redux thunk, redux kullanılan projelerde asenkron işlemleri kolaylaştırmak, bileşen içerisndeki karışıklığı azaltmak ve complex yapıyı bileşenin dışarısına taşımamıza olanak sağlar.

Redux temel yapısı aksiyonların senkron olması üzerine kuruludur. Yani bir eylem dispatch ile tetiklendiğinde bekleme süresi olmadan reducer'a ulaşmalı.

Asenkron işlemlerle uğraşmak istediğimizde, redux thunk devreye girer. Thunk , action oluşturan fonksiyonların basit bir nesne döndürmesi yerine fonksiyon döndrümesine izin verir. Bu sayede aksiyon oluşturan bu fonksiyonların içerisinde api istekleri atılabilir.

## Gif

<img src="/public/ymk_spt_cln_g.gif"/>
