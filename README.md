# Kare ve Küp Hesaplama Projesi

## Proje Amacı
Bu proje, JavaScript'te döngüler kullanarak 1'den 20'ye kadar olan sayıların kare ve küp değerlerini hesaplayarak ekrana yazdırmayı amaçlar. Bu uygulama, temel matematiksel işlemlerle birlikte **for döngüsünü** pekiştirmek için idealdir.

## Kullanılan Yapılar ve Anahtar Kelimeler
- **for döngüsü**: Belirtilen aralıktaki sayılar üzerinde tekrarlı işlemler yapmak için kullanılır.
- **Math.pow() fonksiyonu** veya **çarpma işlemi**: Sayıların karesini ve küpünü hesaplamak için kullanılabilir.
- **console.log()**: Ekrana çıktı almak için kullanılır.

## Değişkenler
- `sayi`: 1'den 20'ye kadar olan her bir sayıyı temsil eder.
- `kare`: `sayi` değişkeninin karesini tutar.
- `kup`: `sayi` değişkeninin küpünü tutar.

## Proje Adımları

1. **Döngü Kurulumu**: 
   - Bir **for döngüsü** oluşturarak `sayi` değişkenini 1'den 20'ye kadar çalışacak şekilde ayarla.
   
2. **Kare ve Küp Hesaplama**:
   - Her döngü adımında `sayi` değişkeninin karesini ve küpünü hesapla.
   - Karesi için `sayi * sayi` ya da `Math.pow(sayi, 2)` kullan.
   - Küpü için `sayi * sayi * sayi` ya da `Math.pow(sayi, 3)` kullan.

3. **Sonuçları Yazdırma**:
   - Döngü her çalıştığında, `console.log()` fonksiyonuyla sayının karesi ve küpünü ekrana yazdır.
   - Her bir sayı için sonuçları düzenli ve okunabilir bir formatta göster.

## Örnek Çıktı Formatı
```plaintext
Sayı: 1, Karesi: 1, Küpü: 1
Sayı: 2, Karesi: 4, Küpü: 8
Sayı: 3, Karesi: 9, Küpü: 27
...
Sayı: 20, Karesi: 400, Küpü: 8000
