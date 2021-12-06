# Spell-Check_with_fastText


Bu çalışmada fastText ile basit bir yazım denetimi uygulaması deniyorum.

FastText, her bir kelimenin, kelimenin kendisine ek olarak n-gramlık bir karakter çantası olarak temsil edilebileceği şekilde alt kelime temsillerini destekler.

FastText kelime vektörlerine dayalı bir yazım denetleyici uygulaması oluşturmaya çalışacağı. Yanlış yazılmış bir kelime verildiğinde eğitimli gömme uzayında bu kelimenin vektör temsiline en yakın kelime vektör temsilini bulmak olacaktır.

Eğer kelime hazinemizde aranılan kelime yer alıyorsa kelimeyi olduğu haliyle bırakacağız, aksi durumda alt kelime temsillerine en yakın olan ile değiştireceğiz.
