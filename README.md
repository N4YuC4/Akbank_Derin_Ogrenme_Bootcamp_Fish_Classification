# Akbank_Derin_Ogrenme_Bootcamp_Fish_Classification
Fish Classification Deep Learning Project for Bootcamp

Bu Proje Akbank Derin Öğrenme Bootcamp için yapılmıştır.

Projenin amacı balık resimleriyle bir tensorflow-keras ile ANN (Artificial Neural Network) modeli eğiterek hangi tür olduğunu sınıflandırmaktır.

Projede en iyi parametreyi bulmak için keras-tuner kutuphanesinden yararlanılmıştır. 

Ayrıca modelin overfitting gibi sorunları engellemek gibi sorunlarla baş edebilmesi için K-Katlı Çapraz Doğrulama (K-Fold Cross Validation) tekniği kullanılmıştır. Bu teknikde verilen K değeri 5 olarak belirlenmiştir. 

Projede %97.89 (kaggle-version 1) ve %95(kaggle-version 2) gibi ortalama accuracy(doğruluk) değerlerine ulaşmıştır. 

Doğruluk değeri CNN (Convolutional Neural Network) modeli ile artırılma potansiyeline sahiptir fakat bootcamp projesi gereği model ANN kullanılarak yapılmıştır.

## Kaggle Proje Linki

[Kaggle](https://www.kaggle.com/code/n4yuc4/fish-classification-ann/)
