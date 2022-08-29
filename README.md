# sudoswap
Sudoswap
sudoswap v69: Sebuah NFT AMM
Beberapa minggu yang lalu, saya menulis litepaper tentang cara lain untuk mendekati finansialisasi NFT, melalui NFT AMM, alih-alih rute fraksionalisasi. Protokol ini, bercanda bernama LSSVM (angguk lidah-di-pipi popularitas memilih nama matematika untuk protokol DeFi), telah lebih disempurnakan setelah beberapa percakapan dengan beberapa orang yang sangat baik di ruang NFT/DeFi. Meskipun MVP testnet masih ada setidaknya satu bulan, saya ingin menarik kembali tirai dan menguraikan cara kerja protokol. Ingatlah ini masih tahap awal, dan banyak hal akan berubah sebelum peluncuran.

gambaran umum

Pada tingkat tinggi, LSSVM terdiri dari banyak kumpulan individu NFT. Setiap kumpulan dikelola oleh satu penyedia likuiditas, dan diparameterisasi oleh kurva ikatan khusus. Pedagang kemudian dapat memilih satu kumpulan untuk berdagang atau berdagang di beberapa kumpulan dengan bantuan agregator. Mirip dengan protokol finansialisasi NFT lainnya, kami berasumsi bahwa NFT lantai akan digunakan terutama, dengan lebih banyak opsi yang dapat disesuaikan dibiarkan untuk iterasi selanjutnya.

Seperti apa bentuk kolam?

