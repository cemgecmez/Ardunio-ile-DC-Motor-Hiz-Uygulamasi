# Ardunio-ile-DC-Motor-Hiz-Uygulamasi
1. Amaç
Arduino üzerinden bir PWM sinyali üreterek motor kontrolünün gerçekleşmesi

2.Gerekli Malzemeler
• Ardunio Uno Geliştirme Kartı
• 9V DC Motor
• 9V Pil
• L293D Motor Sürücü Entegresi
• 1N4007 diyot
• 3 adet 1k Ω direnç
• 3 adet push button
• Kırmızı, Sarı ve Yeşil Ledler (1er tane)
• 3 adet 220Ω direnç

3. Adımlar
• Motor sürücüsü, motor ve Arduino arasındaki gerekli bağlantıları yapınız.
• 3 adet push butonu hız arttır, hız azalt ve motor dönme yönünü değiştir olacak şekilde
ayarlayınız.
• 3 adet farklı renkteki ledi uygun şekilde konumlandırınız.
• Dirençlerini değerlerine göre uygun şekilde led ve butonlar ile kullanınız
• 1N4007 diyotu motor üzerinde oluşabilecek gerilimin geri dönmesini engellemek için
pozitif ucuna bağlayınız.
• Butonları aşağıdaki özelliklerde programlayınız,
o Hız arttır: Her basıldığında, hız mevcut hızından %10 fazla olacak şekilde
arttırılacak. Maksimum hıza ulaşınca Yeşil ve sarı ledler sabit kırmızı led
yanıp/sönecek şekilde programlanacaktır.
o Hız azalt: Her basıldığında, hız mevcut hızından %10 az olacak şekilde
azaltılacak. Minimum hıza ulaşınca Yeşil ve sarı ledler sabit kırmızı led
yanıp/sönecek şekilde programlanacaktır. Ledler yandıktan sonra 2 kez üst üste
basıldığında motor duracaktır.
o Motor yön değiştir ve başlat: Motor ilk kurulum olarak saat yönünde dönecektir.
Motor duruken ilgili butona tek basış ve iki kez basış özelliği programlanmalı,
tek basış saat yönünde, 2 basış anında saat yönünün tersine dönmelidir. Motor
çalışma esnasında ise butona tek basış ile motor durarak çalışma yönünün tersine
dönecektir. Çalışma hızı olarak motor durmadan önceki son hızda çalışacaktır.
• Ledler ise yukarıda bahsedilenlerden hariç olarak, motor hızının minimum ile %20 ve
%80 ile maksimum hız aralıklarında kırmızı led, %20-%80 hız aralığında yeşil led
yanmalıdır. Motor saat yönünde dönüyosa sarı led sönmeli, saat yönünün tersine
dönüyorsa sarı led yanmalıdır.
