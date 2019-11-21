# DynamicCreateTables

Yuvarlak masa ve etrafında sandalyelerin düzenli bir biçimde dinamik oluşmasını sağlayan bir yapıdır.

Masaları ve sandalyelerini Oluşturabilmek için aşağıda belirtilen alanları değiştirmeniz yeterli olacaktır.

mb = Masaların ilk başlangıç Numarası (Kaçtan başlayacak)

ad = Oluşturulacak masa adedi

mx = ilk masanın x konumu (sol kenara olan uzaklık)

my = ilk masanın y konumu (üst kenara olan uzaklık)

        document.addEventListener("DOMContentLoaded", function () {
            //MasaVeSandalyeleriOlustur(mb, ad, mx, my);
            MasaVeSandalyeleriOlustur(1, 14, 150, 100);            
        });
           
Masaları düzenli aralıklarla sağa doğru ekler. Ekran büyüklüğüne göre taşan masayı aşağıya alır, bir aşağısından sağa doğru eklemeye devam eder.

![masalar](https://i.imgyukle.com/2019/11/21/RCu6Mv.jpg)

Sandalyelerde click eventleri mevcuttur.

                        }
                    }
                    // SANDALYE CLİCK EVENT BURAYA EKLENECEK.
                });
                
ibaresinin olduğu yere istediğiniz eventi yazabilirsiniz.

Geliştirmeleri devam edecektir.
