# sentiment-analysis
Analisis sentimen bahasa Indonesia data bersumber dari twitter

Media sosial digunakan oleh banyak instansi untuk mempublikasikan informasi sekaligus menjadi sarana komunikasi dengan masyarakat. Polri melalui Divisi Humas memanfaatkan twitter sebagai salah satu media sosial untuk mempublikasikan berita terkait kepolisian. Masyarakat bisa mengikuti perkembangan terkini suatu isu terkini dan bisa memberikan opininya, selain itu dengan penggunaan media sosial ini masyarakat juga dengan mudah menyampaikan aspirasinya setiap saat. Kepolisian dapat menjadikan media sosial sebagai sumber data yang bisa dimanfaatkan untuk meningkatkan performa pelayanan terhadap masyarakat, dengan cara menganalisa tanggapan masyarakat terhadap suatu isu tertentu.

Penelitian ini menerapkan proses text mining serta menggunakan algoritma Naïve Bayes Classifier untuk mengklasifikasi topik dan sentimen dari tweet tersebut. Penelitian ini menggunakan bantuan API twitter untuk proses pengambilan tweets untuk keperluan data training dan testing. Data training diklasifikasi dengan cara semi unsupervised untuk menentukan label dari setiap data testing. Total keseluruhan data latih sebanyak 4756 record untuk data uji sebanyak 536 record.

Dari keseluruhan proses akan didapat tiga kelas topik yang memiliki sentimen disetiap topiknya. Sentimen positif, negatif dan netral, topik dibagi menjadi tiga kelas yaitu kegiatan polisi, sentimen untuk layanan masyarakat, sentimen pada komentar masyarakat dan sentimen secara keseluruhan. Didapat jumlah sentimen positif sebanyak 181 tweets, negatif 322 tweets dan Netral sebanyak 33 tweets. Untuk hasil pngklasifikasian topik didapat sebanyak 120 tweets dengan topik kegiatan polisi, 49 dengan topik layanan masyarakat dan 367 tweets untuk topik komentar masyarakat. Dari hasil analisis sentimen dari setiap topik didapat respon positif sebesar 55 % untuk topik kegiatan kepolisian, 19,1% respon positif untuk topik komentar masyarakat dan respon positif untuk layanan masyarakat sebesar 91,8%.

Kata Kunci : ***Analisis Sentimen, Klasifikasi Topik, Naive Bayes Classifier, Twitter.***



link : [https://www.kaggle.com/iannarsa/analisis-sentimen-dan-topik-ind?scriptVersionId=20741934](https://www.kaggle.com/iannarsa/analisis-sentimen-dan-topik-ind?scriptVersionId=20741934)
