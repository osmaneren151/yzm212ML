# ManuelCalculatedEigenVectorsValues VS CalculatedByNumpy/linalgVectorValues

## 1. Giriş
Bu çalışmada matris manipülasyonu, özdeğer ve özvektör kavramları inceledik.
Matris manipülasyonu, verilerin matris şeklinde ifade edilmesi ve işlenmesidir.  
Özdeğer, bir lineer dönüşümün vektörü ne kadar büyüttüğünü veya küçülttüğünü gösterir.  
Özvektör ise dönüşüm sonrası yönü değişmeyen vektördür.

## 2. Numpy eig Fonksiyonu
Bu projede NumPy kütüphanesi kullanılmıştır.
`np.linalg.eig(A)` fonksiyonu bir kare matrisin özdeğerlerini ve özvektörlerini hesaplar.
- İlk çıktı özdeğerlerdir  
- İkinci çıktı özvektörlerdir  
Her özvektör, bir özdeğere karşılık gelir.

## 3. Manuel Hesaplama
Özdeğerler manuel olarak da hesaplanabilir.
2x2 matrisler için şu denklem kullanılır:
det(A - λI) = 0
Bu çalışmada özdeğerler manuel olarak hesaplanmış ve NumPy ile karşılaştırılmıştır.

## 4. Karşılaştırma
Manuel hesaplama ile NumPy sonuçlarının aynı olduğu görülmüştür.
Özvektörler birebir aynı görünmeyebilir, ancak şu denklemi sağlarlar:
A * v = λ * v

## 5. Sonuç
Bu çalışmada özdeğer ve özvektörler hem NumPy kullanılarak hem de manuel olarak hesaplanmıştır.
Elde edilen sonuçlar uyumludur. Bu da bu kavramların makine öğrenmesinde numpynin ve linalg modülünün özellikle matematiksel hesaplamalar noktasında önemli olduğunu göstermektedir.
