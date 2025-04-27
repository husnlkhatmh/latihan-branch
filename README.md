# Pyoyek Klasifikasi gambar

Dalam proyek ini dilakukan klasifikasi pada gambar buah-buahan menggunkan transfer learning berbasis MobileNetV2 dan deep learning. Terdapat 5 jenis buah yang akan diklasifikasi oleh model yaitu :

* Apple
* Banana
* Grape
* Mango
* Strawberry

#Link dataset :
https://www.kaggle.com/datasets/marquis03/flower-classification
Dataset tersebut terdiri dari 10.000 gambar yang dibagi menjadi 5 kelas yang di masing-masing kelas terdiri dari 2000 gambar. 

#Akurasi model


| Epoch | Training Accuracy | Training Loss | Validation Accuracy | Validation Loss |
|-------|-------------------|---------------|---------------------|-----------------|
| 1     | 54.48%            | 1.2333        | 81.20%              | 0.5407          |
| 2     | 80.04%            | 0.5591        | 85.40%              | 0.4528          |
| 3     | 82.43%            | 0.5038        | 85.80%              | 0.4238          |
| 4     | 83.77%            | 0.4477        | 85.00%              | 0.4049          |
| 5     | 84.17%            | 0.4362        | 85.60%              | 0.4137          |
| 6     | 85.61%            | 0.3970        | 86.80%              | 0.3747          |
| 7     | 87.00%            | 0.3522        | 86.40%              | 0.3723          |
| 8     | 87.05%            | 0.3621        | 87.60%              | 0.3673          |
| 9     | 88.05%            | 0.3334        | 86.00%              | 0.3805          |
| 10    | 88.39%            | 0.3207        | 87.60%              | 0.3711          |
| 11    | 88.42%            | 0.3272        | 88.20%              | 0.3616          |
| 12    | 89.12%            | 0.2941        | 87.60%              | 0.3805          |
| 13    | 89.84%            | 0.2897        | 86.20%              | 0.3778          |
| 14    | 90.02%            | 0.2780        | 87.40%              | 0.3725          |
| 15    | 91.15%            | 0.2534        | 86.00%              | 0.4019          |

Akurasi Testing :86%

Model ini menunjukkan kinerja yang baik, dengan akurasi pelatihan mencapai 91.15% dan akurasi validasi stabil di atas 85%. Meskipun ada sedikit fluktuasi pada validasi, model ini dapat generalisasi dengan baik.
