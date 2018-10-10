--- 
layout: default 
permalink: 1.0/tr/goruntuluk-orgusu 
lang: tr 
title: Görüntülük Örgüsü 
description: 
---
<p class="girlik">
  Saat kadar minik görüntülükleri (ekranları), telefon görüntülükleri, elüstü görüntülükleri, dizüstü görüntülükleri, masaüstü görüntülükleri, kocaman görüntülükleri ve ulu görüntülükleri olarak öbeklendirilmiş 8 ayrı görüntülük ölçeği uyarlamalı olarak
  kullanılır.
</p>
<p>
  Günümüzde, görüntülük ölçekleri ve görüntülük çözünürlükleri çok çeşitlidir. Bu nedenle uyarlamalı tasarım yapmak bir gerekliliktir. Minik ekranlar ise yakın gelecekte yaygınlaşacaktır. Bu koşullar altında ve doğrultusunda <span class="simget">deveb</span>  daha çok görüntülük aralığı içerir.
</p>
<p></p>
<table class="tablo">
  <thead>
    <tr>
      <th>Görüntülükler</th>
      <th>
        Genel <br>
        <i class="fa fa-minus-square-o" aria-hidden="true"></i> »
        <i class="fa fa-window-maximize" aria-hidden="true"></i>
        <br><span data-metin="olumlu ince">saat » ulu</span>
      </th>
      <th>
        Minik <br>
        <i class="fa fa-minus-square-o" aria-hidden="true"></i>
        <br><span data-metin="olumlu ince">saat</span>
      </th>
      <th>
        Ufak <br>
        <i class="fa fa-mobile" aria-hidden="true"></i>
        <br><span data-metin="olumlu ince">telefon</span>
      </th>
      <th>
        Küçük <br>
        <i class="fa fa-tablet" aria-hidden="true"></i>
        <br><span data-metin="olumlu ince">elüstü</span>
      </th>
      <th>
        Orta <br>
        <i class="fa fa-laptop" aria-hidden="true"></i>
        <br><span data-metin="olumlu ince">dizüstü</span>
      </th>
      <th>
        Büyük <br>
        <i class="fa fa-desktop" aria-hidden="true"></i>
        <br><span data-metin="olumlu ince">masaüstü</span>
      </th>
      <th>
        Kocaman <br>
        <i class="fa fa-television" aria-hidden="true"></i>
        <br><span data-metin="olumlu ince">televizyon</span>
      </th>
      <th>
        Ulu <br>
        <i class="fa fa-window-maximize" aria-hidden="true"></i>
        <br><span data-metin="olumlu ince">ulu görüntülük</span>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Birimleri</th>
      <td>data-gnl</td>
      <td>data-mnk</td>
      <td>data-ufk</td>
      <td>data-kçk</td>
      <td>data-ort</td>
      <td>data-byk</td>
      <td>data-kcm</td>
      <td>data-ulu</td>
    </tr>
    <tr>
      <th>Ölçekler</th>
      <td>0 »</td>
      <td>0 » 300px</td>
      <td>300px »</td>
      <td>576px »</td>
      <td>768px »</td>
      <td>992px »</td>
      <td>1200px »</td>
      <td>1900px »</td>
    </tr>
    <tr>
      <th>Görüntülük Seçme</th>
      <td><span data-metin="ana gri">sınıf</span></td>
      <td>bunu-<span data-metin="ana gri">sınıf</span><br><span data-metin="ana gri">sınıf</span><br>büyükleriyle-<span data-metin="ana gri">sınıf</span><br>büyükleri-<span data-metin="ana gri">sınıf</span></td>
      <td colspan="5">küçükleri-<span data-metin="ana gri">sınıf</span><br>küçükleriyle-<span data-metin="ana gri">sınıf</span><br>bunu-<span data-metin="ana gri">sınıf</span><br><span data-metin="ana gri">sınıf</span><br>büyükleriyle-<span data-metin="ana gri">sınıf</span><br>büyükleri-
        <span
          data-metin="ana gri">sınıf</span>
      </td>
      <td>küçükleri-<span data-metin="ana gri">sınıf</span><br>küçükleriyle-<span data-metin="ana gri">sınıf</span><br>bunu-<span data-metin="ana gri">sınıf</span><br><span data-metin="ana gri">sınıf</span></td>
    </tr>
  </tbody>
</table>

<h3>Görüntülük Yönergeleri</h3>

<p>
  <span class="simget">deveb</span> görüntülük örgüsü küçük görüntülüklerden büyük görüntülüklere doğru olmak üzere belirlenmiş bir yönde varsayılan olarak etki altına alır. Bunun dışında bazı durumlarda geçerli olmak üzere tam tersi yönde veya belirtilen
  tek görüntülük ölçeğinde kullanımı da yapılabilir.
  <br><br> Örneğin bir ögeyi veya alanı dizüstü görüntülüklerine kadar gizlemek istiyorsanız
  <span data-metin="ana">data-ort="küçükleri-gizle"</span> olarak tanımlamanız yeterlidir. Böylelikle dizüstünden küçük görüntülüklerde gizleme yapmış olacaksınız.
</p>

<h4>Kullanımı</h4>
<p>
  Görüntülük örgüsü, <span class="simget">deveb</span>'in özellikleriyle iliştirilmiş şekilde kullanılır. Kesitlik örgüsünde varsayılan kural gerçeli olduğu gibi başka özelliklerde daha ayrı kullanıldığını görmeniz doğaldır.
</p>
<h5>küçükleriyle-?</h5>
<p>
  Tanımlı görüntülükten ve daha küçük görüntülükler. Örnek: data-ort="küçükleriyle-gizle" (english: data-md="hide-with-smaller")
</p>
<h5>küçükleri-?</h5>
<p>
  Belirtildiği görüntülükten küçük görüntülükleri kapsar. Örnek: data-ort="küçükleri-gizle" (english: data-md="hide-smaller")
</p>
<h5>bunu-?</h5>
<p>
  Belirtildiği görüntülükleri kapsar. Örnek: data-ort="bunu-gizle" (english: data-md="hide-this")
</p>
<h5>büyükleri-?</h5>
<p>
  Belirtildiği görüntülüklerden büyük görüntülükleri kapsar. Örnek: data-ort="büyükleri-gizle" (english: data-md="hide-bigger")
</p>
<h5>büyükleriyle-?</h5>
<p>
  Belirtildiği görüntülükler dahil kendisinden büyük görüntülükleri kapsar. Örnek: data-ort="büyükleriyle-gizle" (english: data-md="hide-with-bigger")
</p>