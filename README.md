# YAP-470-Proje
Tobb Etü Yap-470 Dersinin projesi

train.npy ve RF(age).joblib dosyaları yüksek boyuttan dolayı yüklenemedi. Test ederken rf kısmını commit alıp deneyebilirsiniz.

method1_1 ve method1_2 ile farklı parametreler denenip farkları gözlemlenmiştir. Farklar metho1_1'in gender performansı daha iyiyken method1_2 age performansı daha iyidir.

modeller eğitilirken IMDB-WIKI veri setinin 20.000 görüntülü alt kümesi seçilmiştir. Bunun sebebi öznitelik çıkarımının uzun sürmesidir.

İki veri setinin de test setleri .npy uzantılı dosyalar ile eklendi.

Models klasörünün içindeki model1_1 ve model1_2 klasörlerinin içinde modeller saklandı. 

İmdb-wiki veri setinin boyutu büyük olduğu için test veri setinin tamamı eklenemedi. Fakat demo için küçük bir parçası eklendi. Test sonuçlarının tekrarlanması için 1. method olan geleneksel modellerden olan RF modelinin age için olan modeli yüksek boyuttan dolayı yüklenemedi. O yüzden test ederken sıkıntı olacağı için demo kodunda orayı comment satırına aldım. methodx_y.ipynb dosyalarında onu halledemedim o yüzden demo.ipynb dosyasından modellerin test edebilirsiniz. Demo kodunda imdb-wiki veri seti .mat uzantılı dosya ile veriler alındığı için tek bir veri yolu girilip o verinin çıktılarının hesaplanmasını yapamadım.

Herhangi bir sorun olursa m.apaydin@etu.edu.tr e-mail adresime sorunu yazarsanız sevinirim. Teşekkürler.