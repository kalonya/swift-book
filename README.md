# The Swift Programming Language - Türkçe Çeviri Projesi

Bu repo, Apple'ın resmi **[The Swift Programming Language][orijinal-repo]** kitabının Türkçe'ye çevrilmesi amacıyla oluşturulmuş bir projedir. Amacımız, Swift'in resmi dokümantasyonunu Türk diline kazandırarak Türkiye'deki Swift topluluğu için güncel ve erişilebilir bir kaynak sunmaktır.

Kitabın orijinal ve güncel İngilizce versiyonu her zaman [docs.swift.org][orijinal-site] adresinde yayınlanmaktadır ve [Swift-DocC][swift-docc] kullanılarak derlenmektedir.

## Projenin Durumu

**Bu proje aktif olarak çevrilmektedir ve henüz tamamlanmamıştır.**

Çeviri sürecinde hatalar, eksiklikler veya tutarsızlıklar bulunabilir. Çevirinin kalitesini artırmak için topluluğun geri bildirimleri ve katkıları bizim için çok değerlidir. Nihai hedef, çevirinin tamamlanıp `docs.swift.org.tr` (veya benzeri bir adreste) yayınlanmasıdır.

## Katkıda Bulunma

Bu projeye katkıda bulunmak isterseniz çok seviniriz! Yazım hatalarını düzeltmek, çeviri önermek veya yeni bölümleri çevirmek için bir "Pull Request" açabilirsiniz.

Katkıda bulunma süreciyle ilgili daha detaylı bir rehber hazırlanmaktadır. Şimdilik, orijinal projenin [Swift Davranış Kuralları][conduct] belgesine uymanız beklenmektedir.

## Kitabı Yerelde Derleme

Çevirinin web sitesi olarak nasıl göründüğünü test etmek için projeyi kendi bilgisayarınızda derleyebilirsiniz. Bu reponun kök dizininde aşağıdaki komutu çalıştırın:

```bash
docc preview TSPL.docc
```

DocC'yi çalıştırdıktan sonra, tarayıcınızda yerel bir önizleme görüntülemek için `docc`'nin terminalde verdiği linki açın.

> **Not:**
>
> Eğer DocC'yi Swift.org'dan bir toolchain indirerek kurduysanız, `docc` komutu toolchain kurulum yoluna göre `usr/bin/` içinde yer alır. Shell'inizin `PATH` ortam değişkeninin bu dizini içerdiğinden emin olun.
>
> Eğer DocC'yi Xcode indirerek kurduysanız, bunun yerine `xcrun docc preview TSPL.docc` komutunu çalıştırın.

[orijinal-repo]: https://github.com/swiftlang/swift-book
[orijinal-site]: https://docs.swift.org/swift-book/documentation/the-swift-programming-language/
[swift-docc]: https://github.com/apple/swift-docc
[conduct]: https://www.swift.org/code-of-conduct