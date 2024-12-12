# Quantum Genetic Algorithm (QGA)

Genetic Algorithm (GA) adalah sebuah kelas algoritma revolusi yang terinspirasi oleh seleksi alam Darwin. Algoritma ini merupakan metode optimasi heuristik, didasarkan pada mekanisme genetik simulasi seperti mutasi, crossover, dan lain-lain, serta proses dinamika populasi seperti reproduksi, seleksi, dan sebagainya. Untuk mensimulasikan komputer kuantum terbentuk sebuah kelas algoritma genetika dengan nama Quantum Genetic Algorithm (QGA).

Quantum Genetic Algorithm (QGA) adalah metode optimisasi yang menggabungkan prinsip-prinsip algoritma genetik dengan mekanika kuantum. QGA digunakan untuk menemukan solusi optimal dalam masalah yang kompleks dengan memanfaatkan superposisi dan interferensi kuantum.

## Tujuan
Tujuan dari QGA ini adalah:
- Mencari solusi terbaik untuk masalah optimisasi.
- Meningkatkan efisiensi pencarian solusi dibandingkan dengan algoritma genetik klasik.

## Fitness
Fitness dalam konteks QGA mengacu pada nilai yang menunjukkan seberapa baik individu (solusi) dalam populasi memenuhi kriteria yang ditetapkan. Fitness yang lebih tinggi berarti solusi yang lebih baik.

Fitness menggunakan fungsi optimasi f(x)=abs(x-5/2+sin(x)) dengan range 0 <= x <= 15 dengan maksimum x = 11 (1011 dalam bentuk binary), fitness digunakan sebagai visualisasi hasil algoritma

'def Fitness_evaluation(generation):
    i=1; j=1; fitness_total=0; sum_sqr=0;
    fitness_average=0; variance=0;
    for i in range(1,popSize):
        fitness[i]=0'

## Grafik Hasil
Grafik yang dihasilkan menunjukkan perkembangan rata-rata fitness dari generasi ke generasi. 
- **X-Axis**: Generasi
- **Y-Axis**: Rata-rata Fitness
  
![Untitled](https://github.com/user-attachments/assets/7c57eb42-d650-4757-a8df-7c7c42c7f5b2)

## Source

[https://github.com/ResearchCodesHub/QuantumGeneticAlgorithms/blob/master/QGA.py](https://github.com/ResearchCodesHub/QuantumGeneticAlgorithms/tree/master)
http://arxiv.org/ftp/arxiv/papers/0804/0804.1133.pdf

## Video
https://youtu.be/cYd1T6TQvZk
