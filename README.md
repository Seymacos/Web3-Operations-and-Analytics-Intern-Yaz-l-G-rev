# Web3 Hesap Makinesi

Bu proje, Motoko programlama dili kullanılarak oluşturulmuş bir hesap makinesi uygulamasıdır. **Internet Computer** platformu üzerinde çalışan bu uygulama, toplama, çıkarma, çarpma, bölme gibi temel matematiksel işlemleri gerçekleştirir.

## Özellikler
- **Toplama:** Bir sayıyı ekler ve sonucu döner.
- **Çıkarma:** Bir sayıyı çıkarır ve sonucu döner.
- **Çarpma:** Bir sayıyı çarpar ve sonucu döner.
- **Bölme:** Bir sayıyı böler ve sonucu döner (0’a bölme durumunda `null` döner).
- **Temizleme:** Hesap makinesinin içindeki değeri sıfırlar.

## Kullanım
Aşağıdaki fonksiyonlar kullanılarak işlemler yapılabilir:
   - **toplama(s: Int):** `hucre` değişkenine `s` ekler.
   - **cikarma(s: Int):** `hucre` değişkeninden `s` çıkarır.
   - **carpma(s: Int):** `hucre` değişkenini `s` ile çarpar.
   - **bolme(s: Int):** `hucre` değişkenini `s` ile böler. `s = 0` ise `null` döner.
   - **temizle():** `hucre` değişkenini sıfırlar.

## Ekran Görüntüsü
![Sonuçlar](ciktilar.png)

## Geliştiren
Bu proje, Web3 Operations and Analytics staj başvuru süreci için hazırlanmıştır.
Şeyma Coştur
