## Araştırma Cevapları

1- Git, yazılım geliştirme süreçlerinde kullanılan, hız odaklı, dağıtık çalışan bir sürüm kontrol ve kaynak kod yönetim sistemidir.
2- Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portaldır.
3- Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz.
4- Pull request,proje üzerinde bizim tarafımıznda yapılan yeni değişiklerin,asıl projeye aktarılması için söylenen istektir.
5- $ git checkout <branch_name> komutu ile diğer branch'e geçiş yapabiliriz.
6- Git fetch'i kullandığımızda, uzak depodan local çalışma branchimize değişiklikleri commit etmeden ekleriz. Git pull'dan farklı olarak fetching, değişiklikleri local brancheşubenize göndermeden önce gözden geçirmemize olanak tanır. 
Git pull,uzak sunucudaki repository'de değişikliğe uğramış ya da yeni eklenmiş dosyalar varsa bunları indirir ve yereldeki repository ile birleştirir.
Git Merge,Git'de merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. Git merge işlemi sırasında değişikliklerin çoğunu sizin için otomatik olarak entegre eder.
7- Merge conflit,iki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
8- Başka satır değişikliklerinden kaynaklanan bir merge conflit'i çözmek için, farklı branchlerden hangi değişikliklerin yeni bir commit'e dahil edileceğini seçmeliyiz.Bu branchleri birleştirmeden önce bu merge conflit'i yeni bir commitle çözmemiz gerekir