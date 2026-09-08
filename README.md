# HearthDiseasePrediction

Bu çalışmada kalp hastalığı tahmini için Heart Disease Dataset kullanılmıştır. Veri seti, bireylerin çeşitli sağlık göstergelerini içermektedir. Bu göstergeler arasında yaş, cinsiyet, göğüs ağrısı tipi, dinlenme kan basıncı, kolesterol değeri, açlık kan şekeri, elektrokardiyografi sonucu, maksimum kalp atış hızı ve egzersize bağlı anjina gibi değişkenler bulunmaktadır.
Veri setindeki hedef değişken, bireyde kalp hastalığı bulunup bulunmadığını göstermektedir. Bu nedenle problem bir ikili sınıflandırma problemi olarak ele alınmıştır.
Hedef değişken genel olarak şu şekilde yorumlanmıştır:
0 = Kalp hastalığı yok
1 = Kalp hastalığı var
Veri seti modelleme sürecinden önce bağımsız değişkenler ve hedef değişken olarak ayrılmıştır. Daha sonra veri seti eğitim ve test olmak üzere iki parçaya bölünmüştür. Eğitim verisi modellerin öğrenmesi için, test verisi ise modellerin daha önce görmediği veriler üzerindeki başarısını ölçmek için kullanılmıştır.

Veri ön işleme aşamasında ilk olarak veri seti Python programlama dili ile okunmuştur. Veri setindeki sütunlar, veri tipleri ve eksik değerler kontrol edilmiştir. Model başarısını olumsuz etkileyebilecek eksik değerler ve veri uyumsuzlukları incelenmiştir.
Bu çalışmada uygulanan temel veri ön işleme adımları şunlardır:
Veri setinin okunması
Eksik değer kontrolü
Bağımsız değişkenler ve hedef değişkenin ayrılması
Eğitim ve test veri setlerinin oluşturulması
Sayısal verilerin ölçeklendirilmesi
Veri seti, eğitim ve test verisi olarak ayrılmıştır. Genel olarak verinin %80’i eğitim, %20’si test amacıyla kullanılmıştır. Sayısal değişkenlerin farklı ölçeklerde olmasından dolayı StandardScaler yöntemiyle ölçeklendirme işlemi uygulanmıştır.

Bu çalışmada dört farklı kolektif öğrenme yöntemi kullanılmıştır:
1. Random Forest
2. AdaBoost
3. Gradient Boosting
4. Voting Classifier
