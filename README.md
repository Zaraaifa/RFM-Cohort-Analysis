# RFM-Cohort-Analysis

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis data transaksi menggunakan Cohort Analysis dan RFM (Recency, Frequency, Monetary) Analysis.
Analisis ini membantu dalam memahami perilaku pelanggan dan segmentasi berdasarkan pola transaksi mereka.

## Makna Kolom Dataset
| **Kolom**                | **Deskripsi** |
|--------------------------|--------------|
| `transaction_id`         | ID unik untuk setiap transaksi. |
| `product_id`            | ID unik untuk setiap produk. |
| `CustomerID`            | ID unik untuk setiap pelanggan. |
| `transaction_date`      | Tanggal transaksi dilakukan. |
| `online_order`          | Apakah transaksi dilakukan secara online (True/False). |
| `order_status`          | Status pesanan, misalnya "Approved" |
| `brand`                 | Merek produk yang dibeli. |
| `product_line`          | Kategori lini produk, misalnya "Standard". |
| `product_class`         | Kelas produk berdasarkan kualitas atau segmen, seperti "medium" atau "low". |
| `product_size`          | Ukuran produk, misalnya "medium" atau "large". |
| `list_price`            | Harga jual produk sebelum diskon atau promosi. |
| `standard_cost`         | Biaya standar produksi atau akuisisi produk. |
| `product_first_sold_date` | Tanggal pertama kali produk tersebut dijual. |
| `InvoiceDate`           | Tanggal faktur untuk transaksi tersebut. |

## Teknologi yang Digunakan
Python
Jupyter Notebook
Pandas, NumPy
Matplotlib, Seaborn
Scipy
Folium

## Cara Menggunakan
Clone repository ini:
```bash
git clone <repo-url>
cd <repo-folder>
```

## Install dependencies:
```bash
pip install -r requirements.txt
```

## Jalankan notebook di Jupyter:
```
jupyter notebook Analisis_Transaksi_Cohort_&_RFM.ipynb
```

## Hasil Analisis
Cohort Analysis: Menunjukkan pola retensi pelanggan berdasarkan kelompok pembelian pertama mereka.
RFM Analysis: Mengelompokkan pelanggan berdasarkan seberapa baru, sering, dan besar nilai transaksi mereka.

## Kesimpulan
Proyek ini memberikan wawasan mendalam tentang pola transaksi pelanggan menggunakan analisis cohort dan RFM. Dengan memahami pola perilaku pelanggan, bisnis dapat membuat strategi yang lebih efektif untuk meningkatkan retensi dan loyalitas pelanggan.

Mari eksplorasi lebih lanjut tentang eksperimen dengan data dan temukan insight menarik lainnya! 🚀

## Ingin Berkolaborasi?
Saya selalu terbuka untuk diskusi dan kolaborasi lebih lanjut! Jika Anda memiliki ide, saran, atau ingin bekerja sama dalam proyek ini, jangan ragu untuk menghubungi saya.


