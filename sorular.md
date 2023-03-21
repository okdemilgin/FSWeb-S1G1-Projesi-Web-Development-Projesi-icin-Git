# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Kısaca Git bir versiyon kontrol sistemidir. Bu açık kaynaklı versiyon kontrol sistemi sayesinde; projelerin versiyon kontrol takibini yapabilir, dünya çapında projelere katkıda bulunabilir, kendi projelerimizi dünya ile paylaşabilir ve projelerimizin mobilitesini artırabiliriz. Bu sistem sayesinde, bir projede aynı anda birden fazla kişi ile çalışabilir ve bir dosyada yapılan tüm değişiklikleri görüntüleyebiliriz.

2. Git ile GitHub arasında ne fark var?
Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portal.

3. Neden bir branch oluşturuyoruz?
Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar.

4. Pull Request'in amacı nedir?
Fork ettiğimiz bir projenin üzerinde çalışıp, projede yaptığımız değişiklikleri, projenin sahibine pull request olarak gönderebiliriz.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout "branch-name". git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Git fetch: Uzak bir depoda yapılan değişiklikleri çakışma yaratmadan geri yükler.
Git pull: Uzak depoda yapılan değişiklikleri kaydeder ve bunları birleştirir, bu da çakışmalar yaratır.
Remote branchdeki değişikliklerin bilgilerini indirmek için kullanılan fetch ve bu değişiklikleri entegre etmek için kullanılan pull.

7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.

8. Merge conflict'i nasıl çözeriz?
Çakışan kısımların düzeltilmesi ve tekrar merge işlemi uygulanması.
