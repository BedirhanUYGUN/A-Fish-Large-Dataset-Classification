# A-Fish-Large-Dataset-Classification
 
 Akbank Deep Learning - Kaggle Notebook
https://www.kaggle.com/code/bedirhanuygun/a-large-fish-dataset

Gerekli kütüphaneleri yükledim, sonrasında bizlere verilen pdf'teki şekilde verilerimi DataFrame'e çevirdim.
 Veri seti çok büyük olduğu için ve 8 farklı sınıf olduğu için, farklı repoları incelerken denk geldiğim bir methodu uygulamak istedim. Sadece 3 farklı sınıf üzerinde çalışarak işlem süresini uzatmamak istedim.

Verilerimi ise train-test şeklinde (0.8 - 0.2) şekilde ayırdım.

Model seçimini notebook'da belirttiğim gibi, öncesinde de bazı çalışmalarımı Pytorch üzerinde yürüttüm. Pytorch, TensorFlow'dan daha işlevsel ve hızlı olduğunu hem gözlemledim hem de daha performanslı olduğunu düşünüyorum. 
Buradaki katmanları, kodları yazarken GPT'den ve Pytorch'un kendi dökümasyonlarından yardım aldım. 

Sonrasında model eğitimine geçiyorum. Burada overfiting olup olmadığını anlamak için bazı parametreler ekliyorum. Ve sonrasında da bunları grafikler ile inceleyeceğim. 

Modeli eğittikten sonra değerleri ve Confusion Matrix'de sonuçları inceliyorum.
Optimize etmek için ayrı bir şekilde tekrar bir model eğitimi yapıyorum. Ve ondan sonra da ilk modelde olduğu gibi tekrar bir model değerlendirilmesi yaptım. 

En sonda ise Loss ve Accuracy değerlerinin grafiğini koydum
