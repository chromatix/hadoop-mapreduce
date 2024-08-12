# hadoop-mapreduce
# Word Count MapReduce

## Deskripsi
Proyek ini menggunakan Hadoop MapReduce untuk menghitung frekuensi kata dalam teks pembukaan UUD 1945.

## File
- `mapper.py`: Kode untuk map task yang membagi teks menjadi kata-kata.
- `reducer.py`: Kode untuk reduce task yang menghitung jumlah kata.
- `hdfs-wordcount.txt`: Output dari MapReduce job.

## Cara Menjalankan
1. Simpan `mapper.py` dan `reducer.py` di Hadoop cluster.
2. Jalankan Hadoop Streaming dengan `hadoop jar`.
3. Ambil output dari HDFS dan unduh.

## Hasil
Hasil dari job ini akan disimpan di `hdfs-wordcount.txt`.
