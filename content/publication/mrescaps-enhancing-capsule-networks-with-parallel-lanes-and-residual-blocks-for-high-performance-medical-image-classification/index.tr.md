---
abstract: >+
  Medikal görüntülerin sınıflandırılması, doktorların hızlı ve doğru veri
  analizi yapmasını sağlayarak, hastalığın zamanında teşhis edilmesi ve hastaya
  erken müdahale edilme şansını artırır. Ancak, sınıflandırma işlemi elle
  yapıldığında zaman alıcı ve emek yoğun bir süreçtir. Kapsül Ağları (CapsNet)
  mimarisi, görüntüleri parça-bütün ilişkisi içinde değerlendirme yeteneği, veri
  döndürmelerine ve afine dönüşümlere karşı dayanıklılığı ve küçük veri
  kümelerinde iyi performans göstermesi nedeniyle medikal görüntüleri doğru ve
  hızlı bir şekilde sınıflandırmada avantajlara sahiptir. Bununla birlikte,
  CapsNet karmaşık veri kümelerinde düşük performans gösterebilir. Bu çalışmada,
  bu dezavantajın üstesinden gelmek ve karmaşık görüntülerdeki performansını
  artırmak için MResCaps adlı yeni bir CapsNet modeli önerilmektedir. MResCaps,
  her katmanda artan sayıda artık blok kullanarak farklı seviyelerde zengin
  özellik haritaları elde etmeyi amaçlayan paralel yollar kullanarak çeşitli
  medikal görüntülerin sınıflandırılmasında yüksek başarı elde etmeyi
  hedeflemektedir. Modelin performansını değerlendirmek için CIFAR10 veri seti
  ile MedMNIST veri seti koleksiyonundan DermaMNIST, PneumoniaMNIST ve
  OrganMNIST-S veri setleri kullanılmıştır. MResCaps, CIFAR10 veri setinde
  doğruluk açısından CapsNet'i %20 oranında geride bırakmıştır. Ayrıca,
  DermaMNIST, PneumoniaMNIST ve OrganMNIST-S veri setlerinde sırasıyla %96.25,
  %96.30 ve %97.12 AUC değerleri elde edilmiştir. Sonuçlar, önerilen yeni
  MResCaps modelinin, karmaşık ve medikal görüntülerin sınıflandırılmasında
  CapsNet'in performansını geliştirdiğini göstermektedir. Ayrıca, model mevcut
  literatürdeki çalışmalara kıyasla daha iyi bir performans sergilemiştir. Bu
  çalışma, medikal görüntülerin sınıflandırılması için paralel yol mimarisi ve
  zengin özellik kapsülleri odaklı bir yaklaşım sunarak CapsNet tabanlı
  mimarilere yeni bir bakış açısı kazandırmayı amaçlamaktadır.


  The classification of medical images enables physicians to perform expeditious and accurate data analysis, increasing the chances of timely disease diagnosis and early intervention to the patient. However, classification is a time-consuming and labour intensive process when done manually. The Capsule Network (CapsNet) architecture has advantages in accurately and quickly classifying medical images due to its ability to evaluate images within part-whole relationships, robustness to data rotations and affine transformations, and good performance on small datasets. However, CapsNet may demonstrate low performance on complex datasets. In this study, a new CapsNet model named MResCaps is proposed to overcome this disadvantage and enhance its performance on complex images. MResCaps utilizes an increasing number of residual blocks in each layer in parallel lane to obtain rich feature maps at different levels, aiming to achieve high success in the classification of various medical images. To evaluate the model's performance, the CIFAR10 dataset and the DermaMNIST, PneumoniaMNIST, and OrganMNIST-S datasets from the MedMNIST dataset collection are used. MResCaps outperformed CapsNet by 20% in terms of accuracy on the CIFAR10 dataset. In addition, AUC values of 96.25%, 96.30%, and 97.12% were achieved in DermaMNIST, PneumoniaMNIST, and OrganMNIST-S datasets, respectively. The results show that the proposed new model MResCaps improves the performance of CapsNet in the classification of complex and medical images. Furthermore, the model has demonstrated a better performance in comparison with extant studies in the literature. This study aims to contribute significantly to the literature by introducing a novel perspective on CapsNet-based architectures for the classification of medical images through a parallel-laned architecture and a rich feature capsule-focused approach.


url_pdf: https://onlinelibrary.wiley.com/doi/10.1002/ima.23108
title: "MResCaps: Enhancing capsule networks with parallel lanes and residual
  blocks for high-performance medical image classification"
publication_types:
  - "2"
authors:
  - Sümeyra Büşra Şengül
  - İLKER ALİ ÖZKAN
doi: 10.1002/ima.23108
publication: International Journal of Imaging Systems and Technology
publication_short: Int J Imaging Syst Technol.
featured: true
tags:
  - capsule network
  - classification
  - complex image
  - medical image
  - residual block
image:
  filename: mrescaps.png
date: 2024-05-31T11:27:53.514Z
publishDate: 2024-05-31T11:27:53.514Z
---
Sümeyra Büşra ŞENGÜL, **Ilker Ali OZKAN** (2024). MResCaps: Enhancing capsule networks with parallel lanes and residual blocks for high-performance medical image classification, Int J Imaging Syst Technol.,  2024; 34(4):e23108. https://doi.org/10.1002/ima.23108
