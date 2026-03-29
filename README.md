## Problem Tanımı ve Hedef Belirleme

Günümüzde e-ticaret platformlarında yer alan kullanıcı yorumları, ürünler hakkında önemli bilgiler içermektedir. Ancak bu yorumların sayıca fazla olması, kullanıcıların tüm yorumları manuel olarak incelemesini zorlaştırmaktadır.

Bu projede, Amazon platformundan elde edilen kullanıcı yorumları kullanılarak duygu analizi yapılması amaçlanmaktadır. Veri setinde doğrudan duygu etiketi bulunmadığından, yorumlara ait yıldız (rating) bilgileri kullanılarak duygu sınıfları oluşturulacaktır. Bu kapsamda, 4 ve 5 yıldızlı yorumlar "pozitif", 1 ve 2 yıldızlı yorumlar "negatif" olarak etiketlenecek, 3 yıldızlı yorumlar ise belirsiz (neutral) kabul edilerek analiz dışında bırakılacaktır.

Bu problemin seçilme nedeni, gerçek dünya verileri üzerinde veri madenciliği tekniklerini uygulamak ve metin verilerinden anlamlı çıkarımlar elde edebilmektir.

Bu çalışmada yanıtlanması hedeflenen araştırma sorusu şudur:
"Bir kullanıcı yorumunun metin içeriğine bakılarak duygu durumu (pozitif/negatif) ne kadar doğru tahmin edilebilir?"

Projenin temel hedefi, verilen bir ürün yorumunun duygu durumunu doğru şekilde sınıflandırabilen bir model geliştirmek ve farklı makine öğrenmesi yöntemlerini karşılaştırarak en başarılı yaklaşımı belirlemektir.