---
abstract: >+
  Medikal görüntülerin tanınması ve analiz edilmesi, hastalıkların erken tespiti ve tedavi planlaması için kritik öneme sahiptir. Hastaların bireysel ihtiyaçları ve hastalık geçmişine dayalı uygun tedavi seçeneklerinin belirlenmesi, bu süreçte önemli bir rol oynar. Derin öğrenme teknolojileri, görüntüleri hızlı ve doğru bir şekilde analiz edebildikleri için sağlık alanında yaygın olarak kullanılmaktadır. Ancak, tıbbi görüntülerdeki her bir nesne potansiyel olarak hastalık bilgisi barındırabileceğinden, görüntüleri minimum bilgi kaybıyla analiz etmek önemlidir. Bu bağlamda, Capsule Network (CapsNet) mimarisi, görüntülerdeki nesnelerin konum ve özelliklerini kapsüller olarak saklayarak bilgi kaybını azaltmayı amaçlayan önemli bir yaklaşımdır. Bununla birlikte, CapsNet her bir nesneyle ilgili bilgileri koruduğu için, karmaşık görüntülerde birden fazla nesnenin varlığı CapsNet'in performansını olumsuz etkileyebilir. Bu çalışmada, CapsNet'in performansını artırmak amacıyla HMedCaps adında yeni bir model önerilmektedir. Önerilen modelde, özellik çıkarım katmanında Residual Block ve FractalNet modülünün birlikte kullanılmasıyla daha derin ve hibrit bir yapı geliştirilmesi hedeflenmiştir. Ağın derinliği arttıkça çıkarılan özellik sayısını artırarak zengin özellik haritaları elde etmek amaçlanırken, bu modüllerdeki geçiş bağlantıları sayesinde ağda derinlikle birlikte ortaya çıkabilecek vanishing gradient probleminin önlenmesi hedeflenmiştir. Ayrıca, kapsül aktivasyonunu özelleştirerek ayırt edici kapsülleri daha belirgin hale getirmek için yeni bir squash fonksiyonu önerilmiştir. Çalışmanın değerlendirilmesi için karmaşık görüntüler içeren CIFAR10 veri seti, retinal görüntüler içeren RFMiD veri seti ve kan hücresi görüntüleri içeren Blood Cell Count Dataset veri seti kullanılmıştır. Önerilen model, temel CapsNet ve literatürdeki çalışmalarla karşılaştırıldığında, karmaşık görüntülerde performansın iyileştiği ve tıbbi görüntü analizi alanında daha doğru sınıflandırma sonuçları elde edildiği gözlemlenmiştir. Önerilen hibrit HMedCaps mimarisinin, tıbbi görüntü analizi alanında daha doğru teşhisler yapma potansiyeline sahip olduğu düşünülmektedir.
  
  Recognizing and analyzing medical images is crucial for disease early
  detection and treatment planning with appropriate treatment options based on
  the patient's individual needs and disease history. Deep learning technologies
  are widely used in the field of healthcare because they can analyze images
  rapidly and precisely. However, because each object on the image has the
  potential to hold illness information in medical images, it is critical to
  analyze the images with minimal information loss. In this context, Capsule
  Network (CapsNet) architecture is an important approach that aims to reduce
  information loss by storing the location and properties of objects in images
  as capsules. However, because CapsNet maintains information on each object in
  the image, the existence of several objects in complicated images can impair
  CapsNet's performance. This work proposes a new model called HMedCaps to
  improve the performance of CapsNet. In the proposed model, it is aimed to
  develop a deeper and hybrid structure by using Residual Block and FractalNet
  module together in the feature extraction layer. While it is aimed to obtain
  rich feature maps by increasing the number of features extracted by deepening
  the network, it is aimed to prevent the vanishing gradient problem that may
  occur in the network with increasing depth with these modules with skip
  connections. Furthermore, a new squash function is proposed to make
  distinctive capsules more prominent by customizing capsule activation. The
  CIFAR10 dataset of complex images, RFMiD dataset of retinal images, and Blood
  Cell Count Dataset dataset of blood cell images were used to evaluate the
  study. When the proposed model was compared with the basic CapsNet and studies
  in the literature, it was observed that the performance in complex images was
  improved and more accurate classification results were obtained in the field
  of medical image analysis. The proposed hybrid HMedCaps architecture has the
  potential to make more accurate diagnoses in the field of medical image
  analysis.



url_pdf: https://link.springer.com/article/10.1007/s00521-024-10147-9
title: "HMedCaps: a new hybrid capsule network architecture for complex medical images"
publication_types:
  - "2"
authors:
  - Sümeyra Büşra Şengül
  - İLKER ALİ ÖZKAN
doi: 10.1007/s00521-024-10147-9
publication: "Neural Computing and Applications"
publication_short: Neural Comput & Applic
featured: true
tags:
  - CapsNet
  - Complex image
  - FractalNet
  - Medical image analysis
  - Squash function
image:
  filename: "hmedcaps.png"
date: 2024-08-14T16:23:27.845Z
publishDate: 2024-05-31T11:27:53.514Z
---
Sümeyra Büşra ŞENGÜL, **Ilker Ali OZKAN** (2024). HMedCaps: a new hybrid capsule network architecture for complex medical images, Neural Comput & Applic. https://doi.org/10.1007/s00521-024-10147-9
