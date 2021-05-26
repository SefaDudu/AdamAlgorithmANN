# AdamAlgorithmANN
Loss Function Ve Optimizer
Sistem, yaptığı tahminleri için hata kontrolü yapar ve hatayı sürekli olarak minimize etmeye çalışır. Bunun için hatayı hesaplayıp(loss function) beklenen sonuca yakınsamaya(optimizer kullanır) yani hatayı azaltmaya çalışır. Loss function ile hata hesaplanırken optimizer(örneğin: Adam) ile en düşük hata alınacak ihtimaller bulunulmaya çalışılır.

Mean Squared Error (MSE) : Regresyon problemleri için kullanılmakta. Eğer sürekli sayısal bir değer tahmini yapılacaksa kullanılabilir. Tahmin edilen ve gerçek değerler arasındaki kare farkı ortalaması alınarak hesaplanır.

![image](https://user-images.githubusercontent.com/77778888/119717467-0174a100-be6f-11eb-9316-b9947ebd7370.png)
ADAM ALGORİTHM
Aktivasyon fonksiyonları çok katmanlı yapay sinir ağlarında doğrusal olmayan (non-linear) dönüşüm işlemleri için kullanılmaktadır. 
Adam, klasik stokastik gradyan azaltma yöntemi yerine kullanılabilecek daha verimli, adaptif bir optimizasyon algoritmasıdır. Yani her bir parametre için dinamik bir şekilde öğrenme oranını (learning rate) günceller . Hesaplama yükü olarak verimlidir ve düşük bellek gereksinimlerine ihtiyaç duyar. Adam, RMS-Prop ve Momentum ile birlikte gradyan düşürme yöntemlerine benzer bir parametre güncelleme metodu kullanmaktadır.   

![image](https://user-images.githubusercontent.com/77778888/119717578-249f5080-be6f-11eb-8952-4b294ee86919.png)


 

