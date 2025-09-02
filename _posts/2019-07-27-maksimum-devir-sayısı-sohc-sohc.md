---
layout: post
title: "Maksimum devir sayısını ne belirler? SOHC ve Dohc nedir? Farkları nelerdir? Motronic nedir? Sensörleri nelerdir?"
description: "Maksimum devir sayısını ne belirler? SOHC ve Dohc nedir? Farkları nelerdir? Motronic nedir? Sensörleri nelerdir?"
category: [FSAE]
keywords: "motronic, sohc, dohc, eksantrik, kam mili, subap, fsae, devir, maksimum"
author: Furkan MISIR
image: "/img/doge.png"
---
### Bir motorun maksimum devir sayısını belirleyen faktörler nelerdir?
---
Motor devri, araçta bulunan motorun krank milinin bir dakikada dönme sayısıdır. Motor devir saati sayesinde de biz gösterge panelinde bu devri okuyabiliriz. Devir, aracın vites yükseltmeye uygun olduğuna (vites istemesi) ya da düşürmeye uygun olduğunu anlamak içinde bakabiliriz. Bir motorun devir sayısını pistonun hızı belirler. Pistonun maksimum hızını düşürmek motordaki stres kuvvetlerini azaltacağı için motorun devir sayısı artar. Bu durumu sağlamak için pistonun çalışma aralığı (stroke) küçültülürse pistonun hızı azalır. Üreticiler motorun devir sayısını artırmak için stresi azaltıp piston yarı çapını büyülterek aynı boyuttaki bir motorun daha yüksek devirlerde çalışması sağlanır.

### DOHC-SOHC nedir? Farkları nelerdir?
---
İçten yanmalı motorları, eksantrik miline ve subaplarına göre ayrıştıran ifadelerdir. Bunun yanında OHV ve SV ifadeleri de bulunur. DOHC (Double overhead camshaft) ve SOHC (Single overhead camshaft), OHV (Overhead valve) ve SV (Side valve, flathead) aksine üstten eksantrikli sistemdir. OHV ve SV bloktan eksantriklidir. SV-OHV-SOHC-DOHC sırasıyla motor devri ve verimi artarak gelişmiştir. SV, eksantrik mili ve subapın motor bloğunda olduğu sistemdir. Sıkıştırma oranı az olduğundan yüksek devirlere ulaşamaz ama yüksek devirlere ulaşamayacağı için de titreşiminin az olması avantajı vardır. Eskiden yaygın olsa da günümüzde çok özel motorlarda kullanılmaktadır. OHV, eksantrik mili yine motor bloğunda olmasına rağmen subaplar motor bloğunun üzerindedir. Eksantrik milinden itici bir çubuk vasıtası ve külbitör mekanizması sayesinde subaplar harekete geçiriliyor. SV motorlarda olduğu gibi genelde piston başına Emme ve egzoz olarak tek subaptır. Sıkıştırma oranı SV motora göre fazla olduğundan daha yüksek devirlere ulaşabilir. SOHC sistemi SV ve OHV aksine üstten eksantriklidir. Piston başına emme ve egzoz olmak üzere tek subap düşer. Sıkıştırma oranı SV ve OHV ye göre daha yüksek olduğundan, daha yüksek devirlere ulaşıp daha verimlidir. DOHC, üstten eksantrikli bir sistemdir. SOHC, SV ve OHV den daha yüksek sıkıştırma oranına sahip olduğundan daha yüksek devirlere ulaşıp daha verimlidir. SOHC den farkı çift eksantriklidir. Piston başına iki subap düşer, iki emme iki egzoz olmak üzere. Günümüzde en yaygın sistemdir.

**NOT:** OHC ve CIH gibi diğer motor sistemleri de vardır.

![sohc-dohc-ohc-sv](/img/dohcsohc.jpg)

### Motronic işletim sistemiyle çalışan bir motorun sensor listesi?
---
Motorun hava, yakıt beslemesinin ve ateşleme sisteminin elektronik olarak kontrolünü ve optimizasyonunu sağlar. Motronic ECU olarak da yazılır, ECU motor kontrol ünitesi anlamına gelmektedir. Motronic ECU Robert Bosch tarafından tasarlanmıştır. İlk olarak BMW 1979 da 732İ modeli arabasına monte etmiştir. Günümüzde Motronic motor kontrol ünitelerinin yolunu açması ile ASR (Antipatinaj sistemi) ve ESP (Elektronik stabilite programı) gibi farklı motor kontrol üniteleri de bulunmaktadır. Elektronik kontrol üniteleri olmadan önce mekanik kontrol sistemleri kullanılmaktaydı. Mekanik kontrol sistemleri, yüksek miktarda benzin tüketimine sebep olmakla kalmayıp yüksek miktarda zararlı emisyona da sebep oluyordu. Günümüzde ise Motronic sistemi çok sayıda sensor yardımı ile püskürtme ve ateşleme için en iyi değerleri hesaplıyor. Bu hesaplama dakikada altı binden fazla kez gerçekleşiyor.  Sensörrler aracılığıyla mikro işlemciye her püskürtme ve ateşleme işlemi için emilecek hava miktarı, motor devri, krank mili konumu ve emilen havanın sıcaklığı ve motor sıcaklığı verileri sağlanıyor. Bu bilgiler sayesinde Motronic, motorda daima ideal hava-yakıt karışımı miktarının tam doğru anda ateşlenmesini garantiliyor. Motronic sistemi aynı zamanda motorunun uzun ömürlü olmasını da sağlamaktadır. Araç parçalarının ömür sürelerini de hesaplayarak sistemde kullanır. Motronic sisteminin mikro işlemci ve belleğine bu önemli verileri yollayıp hesaplanmasını sağlayan sensörler ise şunlardır;
1.	Hava debimetresi
2.	Emilen hava sıcaklık sensörü
3.	Mutlak basınç sensörü
4.	Gaz pedal konum sensörü
5.	Gaz kelebeği konum sensörü
6.	Oksijen sensörü
7.	Motor soğutma sıvısı sıcaklık sensörü
8.	Yakıt sıcaklık sensörü
9.	Egzoz geri basınç sensörü
10.	Kick-down sensörü
11.	Turbo basınç sensörü
12.	Darbe sensörü
13.	Yağ sıcaklık sensörü
14.	Motor yağ basınç ve seviye sensörü
15.	Kran konum sensörü
16.	Vuruntu sensörü
