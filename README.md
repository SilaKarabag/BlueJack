# 🃏 Bluejack Kart Oyunu

Bu proje, Java ile geliştirilmiş, konsol tabanlı basit bir kart oyunudur. Popüler Blackjack oyunundan esinlenilmiştir, ancak temel hedef 21 yerine **20**'ye ulaşmaktır. Oyuncu, bilgisayara karşı 3 tur boyunca mücadele eder.

## 🕹️ Oynanış

Oyunun temel kuralları oldukça basittir:

- **Amaç:** Elinizdeki kartların toplam değerini 20'ye mümkün olduğunca yaklaştırmak, ancak 20'yi geçmemek.
- **Turlar:** Oyun toplam 3 turdan oluşur.
- **Rakip:** Bilgisayara (Computer) karşı oynanır.
- **Oyuncu Seçenekleri:**
  1.  **Kart Çek (Draw a card):** Desteden yeni bir kart çeker ve elinize eklersiniz.
  2.  **Dur (Stand):** Kart çekmeyi bırakır ve sırayı bilgisayara verirsiniz.
  3.  **Elden Kart Oyna (Play a card from hand):** _(Bu özellik şu an için geliştirme aşamasındadır.)_

Eğer bir oyuncunun elindeki kartların toplamı 20'yi geçerse, o turu otomatik olarak kaybeder ("Busted"). Her iki oyuncu da "Dur" dediğinde, 20'ye en yakın olan turu kazanır.

## 🚀 Nasıl Çalıştırılır?

Projeyi yerel makinenizde çalıştırmak için Java'nın yüklü olması yeterlidir.

1.  Kodları `Play.java` adıyla bir dosyaya kaydedin.
2.  Terminal veya komut istemcisini açın ve dosyanın olduğu dizine gidin.
3.  Aşağıdaki komut ile kodu derleyin:
    ```bash
    javac Play.java
    ```
4.  Derleme başarılı olduktan sonra aşağıdaki komut ile oyunu başlatın:
    ```bash
    java Play
    ```

## 🛠️ Kod Yapısı ve Geliştirme Notları

Bu proje, temel Java bilgisiyle yazılmış tek bir `Play.java` dosyasından oluşmaktadır. İçerisinde `Card` adında bir inner class barındırır.
