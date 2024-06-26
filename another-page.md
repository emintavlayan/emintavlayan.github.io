---
layout: default
---

## Interactive Test Sayfasi Deneme 

<div id="filter-buttons-section1">
  <div>
    <span>Frequency:</span>
    <button class="toggle-btn" data-filter="daily" onclick="toggleFilter(this, 'frequency', 'daily')">Daily</button>
    <button class="toggle-btn" data-filter="monthly" onclick="toggleFilter(this, 'frequency', 'monthly')">Monthly</button>
    <button class="toggle-btn" data-filter="yearly" onclick="toggleFilter(this, 'frequency', 'yearly')">Yearly</button>
  </div>
  <div>
    <span>LINAC Type:</span>
    <button class="toggle-btn" data-filter="c-arm" onclick="toggleFilter(this, 'type', 'c-arm')">C-Arm</button>
    <button class="toggle-btn" data-filter="o-ring" onclick="toggleFilter(this, 'type', 'o-ring')">O-Ring</button>
  </div>
</div>

## Mekanik testler

**Lazer kontrolu**{: .daily .c-arm .o-ring}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ultricies ante at dolor rhoncus pulvinar. Curabitur lorem mauris, hendrerit vitae feugiat a, tempus ac purus. Maecenas efficitur venenatis feugiat. Phasellus vitae velit sed quam gravida scelerisque ac non arcu. Pellentesque efficitur nibh sit amet lectus dignissim mollis. Pellentesque pellentesque vehicula leo, at dictum ligula vestibulum ac.
{: .daily .c-arm .o-ring}

**SSD kontrolu**{: .daily .monthly .c-arm}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ultricies ante at dolor rhoncus pulvinar. Curabitur lorem mauris, hendrerit vitae feugiat a, tempus ac purus. Maecenas efficitur venenatis feugiat. Phasellus vitae velit sed quam gravida scelerisque ac non arcu. Pellentesque efficitur nibh sit amet lectus dignissim mollis. Pellentesque pellentesque vehicula leo, at dictum ligula vestibulum ac.
{: .daily .monthly .c-arm}

**Isik alan radyasyon alan uyumu**
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ultricies ante at dolor rhoncus pulvinar. Curabitur lorem mauris, hendrerit vitae feugiat a, tempus ac purus. Maecenas efficitur venenatis feugiat. Phasellus vitae velit sed quam gravida scelerisque ac non arcu. Pellentesque efficitur nibh sit amet lectus dignissim mollis. Pellentesque pellentesque vehicula leo, at dictum ligula vestibulum ac.
{: .monthly .yearly .c-arm}

**Kapi interlock kontrolu**
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ultricies ante at dolor rhoncus pulvinar. Curabitur lorem mauris, hendrerit vitae feugiat a, tempus ac purus. Maecenas efficitur venenatis feugiat. Phasellus vitae velit sed quam gravida scelerisque ac non arcu. Pellentesque efficitur nibh sit amet lectus dignissim mollis. Pellentesque pellentesque vehicula leo, at dictum ligula vestibulum ac.
{: .daily .monthly .yearly .c-arm .o-ring}

## Dozimetrik testler

### output kontrolu{: .daily .monthly .yearly .c-arm .o-ring}

Gunluk output kontrolleri icin kullanimi kolay cihazlarla kontroller yapilabilir. Daily QA gibi cihazlarinin bilinen Iyon odasi olcumleri ile dogru bir sekilde Cross-Calibre edilmis oldugundan emin olunmalidir
{: .daily .monthly .yearly .c-arm .o-ring}

Aylik kontrollerde, output kontrolu iyon odasi ve kati fantomlarda pratik bir sekilde yapilabilir. Yine de SSDL ile takip edilen su icinde referans dozimetre olcumleri ile cross calibrasyon katsayilarinin dogrulugundan emin olunmalidir. yukarida bahsedilen gunluk output kontrolu icin kullanilan tum sistemlerin AYlik kontrol sirasinda halen uyumlu olduklari da test edilmelidir.
{: .monthly .yearly .c-arm .o-ring}

Yillik output kontrolleri, direkt olarak PSDL evya SSDL sertifikasi olan iyon odalari ile referans kosullarda gerceklestirilmelidir. Gunluk ve  Aylik kontrollerde kullanilan tum sistemler ve gerekli katsayilar yillik olcum sirasinda yeniden olculmeli ve teyit edilmelidir
{: .yearly .c-arm .o-ring}

### Su fantomunun kurulmasi{: .yearly .c-arm}

**Carm linaklarda normal sekilde kendi ayak mekanizmasi ile sabitlenir**{: .yearly .c-arm}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ultricies ante at dolor rhoncus pulvinar. Curabitur lorem mauris, hendrerit vitae feugiat a, tempus ac purus. Maecenas efficitur venenatis feugiat. Phasellus vitae velit sed quam gravida scelerisque ac non arcu. Pellentesque efficitur nibh sit amet lectus dignissim mollis. Pellentesque pellentesque vehicula leo, at dictum ligula vestibulum ac.
{: .yearly .c-arm}

**Laserler ve alan isigi ile isocenter a yerlestirilir**{: .yearly .c-arm}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ultricies ante at dolor rhoncus pulvinar. Curabitur lorem mauris, hendrerit vitae feugiat a, tempus ac purus. Maecenas efficitur venenatis feugiat. Phasellus vitae velit sed quam gravida scelerisque ac non arcu. Pellentesque efficitur nibh sit amet lectus dignissim mollis. Pellentesque pellentesque vehicula leo, at dictum ligula vestibulum ac.
{: .yearly .c-arm}

**Halcyon icin ayaklarindan kaldirilarak masa uzerine konur**{: .yearly .o-ring}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ultricies ante at dolor rhoncus pulvinar. Curabitur lorem mauris, hendrerit vitae feugiat a, tempus ac purus. Maecenas efficitur venenatis feugiat. Phasellus vitae velit sed quam gravida scelerisque ac non arcu. Pellentesque efficitur nibh sit amet lectus dignissim mollis. Pellentesque pellentesque vehicula leo, at dictum ligula vestibulum ac.
{: .yearly .o-ring}

**Isocenter goruntuleme sistemleri ile bulunur**{: .yearly .o-ring}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ultricies ante at dolor rhoncus pulvinar. Curabitur lorem mauris, hendrerit vitae feugiat a, tempus ac purus. Maecenas efficitur venenatis feugiat. Phasellus vitae velit sed quam gravida scelerisque ac non arcu. Pellentesque efficitur nibh sit amet lectus dignissim mollis. Pellentesque pellentesque vehicula leo, at dictum ligula vestibulum ac.
{: .yearly .o-ring}

[back](./)
