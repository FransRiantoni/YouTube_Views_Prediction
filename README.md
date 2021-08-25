# YouTube_Views_Prediction

![Project Image](https://1.bp.blogspot.com/-QmorW9uzfJo/X4VnZF86rkI/AAAAAAAAA0Y/8pv8AFEmlCYo45SSKWtMmrBxaqI_rliDACLcBGAsYHQ/s655/ytviews.jpg)

> **How to get more views on your own channel ?**

-----

### Table of content's:
your selection header will be used to reference location of destination.
- [Short Project Blurb](#Short_Project_Blurb)
- [Goals](#Goals)
- [Matrics](#Matrics)
- [Conclusion and Recommendation](#Conclusion_and_Recommendation) 
- [Preference](#Preference)
- [Licence](#Licence)
- [Author info](#Author info)
 
-----

## **Short Project Blurb**
salah satu hal yang dibutuhkan dalam proses monetasi channle youtube ialah harus memiliki jam tayang sebanyak 4000 jam selama 12 bulan dan telah memiliki minimal 1000 subsciber. untuk mendapatkan syarat lamanya jam tayang, pengunjung tidak hanya diupayakan dapat berkunjung namun mereka harus mampu menonton selama mungkin pada konten kita.
Pentingnya jumlah views yang tinggi akan sangat mendukung jumlah waktu tayang content tersebut.
Data yang digunakan dalam analisa ini berasal dari YouTube satatistic pada negara india terdiri dari 36790 data dan 1390 Channels yang dikumpulkan pada Desember 2017- June 2018. berdasarkan data tersebut, memunculkan pertanyaan bagaimana kita bisa standing/berhasil dalam membangun channel youtube di india?. Hal ini tentunya akan terjawab dengan analisa karakteristik dari user yang berasal dari india dan memestikan beberapa parameter penting yang harus dibentuk sesempurna mungkin. Sehingga hal inilah yang melatarbelakangi analisa data YouTube views ini guna menemukan tips dan trick untuk menghasilkan channel youtube yang berkualitas dengan view yang banyak.

dimulai dengan ditemukannya beberapa parameter panting yang harus dibentuk secara sempurna, saya akan memberikan beberapa rekomendasi solusi untuk mengoptimasi. selain itu, hasil prediksi tentukan dapat disimpan dan disimulasikan kembali pada data test yang lain untuk memprediksi kesuksesan dari channel yang dibangun.

-----
## **Goals** : 
- Help others to having tips and trick for building channel YouTube in India based on features important.
- Know the carracteristics of people who had watched YouTube in India.
- Build Modeling.

## **Matrics**:
- Data pickle of modelling.
- Percentage of impact from the most important features.

-------
## Modelling Result

| Evaluation\Model | Linear | DecisionTree | SVR | RandomForest |
| ---------------- | ------ | ------------ | --- | ------------ |
| MAE | 0.34 | 0.26 | 0.40 | 0.20|
| RSME | 0.44 | 0.36 | 0.52 | 0.26|
| R SCORE | 0.35 | 0.57 | 0.10 | 0.77|

Berdasarkan evaluasi modelling tersebut, RandomForest memberikan hasil evaluasi yang sangat bagus dilihat dari rendahnya nilai MAE dan RMSE serta tingginya nilai R Score. Sudah dilakukan optimasi Hyperparameter pada RandomForest dan sistem grid secara random namun tidak memberikan hasil yang signifikan berubah.

----

## Conclusion and Recommendation

sertakan gambar feature importantnya,
Kasih rekomendasinya dari conclusi yang di code nya.


----

https://www.youtube.com/watch?v=bpdvNwvEeSE 
