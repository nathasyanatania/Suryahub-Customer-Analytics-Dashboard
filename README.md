# Suryahub-Customer-Analytics-Dashboard
Interactive Customer Behaviour Dashboard for SuryaHub Built with Google Looker Studio

# Dashboard Customer Behaviour - SuryaHub

Dashboard interaktif untuk monitoring customer behaviour SuryaHub dibuat menggunakan Google Looker Studio dari data Excel penjualan.

## Tujuan
- Evaluasi efektivitas program loyalitas pelanggan
- Identifikasi peluang personalisasi campaign marketing
- Menyediakan insight untuk pengambilan keputusan strategis (target: marketing director & tim customer experience)

## Isi Dashboard
1. **Customer Demographics & Segmentation** — usia, gender, income level
2. **Geographic & Category Performance** — performa per lokasi & tren kategori pembelian
3. **Loyalty Program Effectiveness** — perbandingan member vs non-member
4. **Channel & Social Media Influence**
5. **Purchase Intent Analysis** — needs-based, wants-based, impulsive
6. **High-Value Customer Profiling** — profil pelanggan bernilai tinggi (top 20%)

## Live Dashboard
Klik di sini untuk membuka dashboard *(https://datastudio.google.com/reporting/e3812d73-41b0-41f7-967f-598cd5c85198)*

## Tools
- Google Looker Studio (Data Studio)
- Excel (data source & preprocessing)

## Key Insight
1. **Customer Demographics & Segmentation**
   - Rata-rata usia customer  Surya Hub 35 tahun dengan rentang usia 18–50 tahun.
   - Komposisi gender cukup seimbang Female sebanyak 265 orang dan Male 234 orang.
   - Income level hampir seimbang 50,1 : 49,9 yaitu Middle Income sebanyak  250 orang dan High Income sebanyak 249 orang tidak ada segmen dominan tunggal.  Basis customer SuryaHub relatif terdiversifikasi bukan niche (fokus yang spesifik) ke satu grup demografis.
  - Kelompok demografis Female usia 35-44 tahun merupakan penyumbang Purchase Amount tertinggi, sementara kelompok Male usia 18-24 tahun menyumbang nilai pembelian terendah. Total nilai pembelian dari kelompok Female jauh lebih mendominasi dibandingkan kelompok Male di hampir semua kategori usia.

2. **Geographic & Category Performance**
   - Makassar adalah kota yang menduduki posisi pertama paling banyak dari jumlah customer yaitu 95 orang dan total revenue sebesar Rp421 juta, Posisi kedua kota Jakarta dengan revenue sebesar Rp373 juta. Selisih revenue antar kota tidak terlalu ekstrem. Revenue berkisar pada range antara Rp313 hingga 421 juta artinya performa cukup merata di 6 kota.
   - Kategori revenue tertinggi pada produk Food & Beverages, Health Care, Software & Apps sehingga layak menjadi fokus alokasi inventori/campaign.
  
3. **Loyalty Program Effectiveness**
   - Average Order Value member sebesar Rp4,12jt lebih rendah dari non-member sebesar Rp4,38jt.
   - Frekuensi beli member 6,66x vs non-member 6,99x dan brand loyalty score non member 3,06 vs  member 3,01 nyaris hampir sama.
   - Program loyalitas saat ini tidak menunjukkan dampak positif ke perilaku beli ini temuan paling penting untuk dibawa ke leadership karena mengindikasikan diperlukan peninjauan ulang program mungkin insentifnya kurang menarik atau member yang join justru bukan heavy-spender.
   - Member sedikit lebih condong ke Need-based (70 vs 59 non-member), non-member sedikit lebih ke Wants-based (64 vs 62). 

4. **Channel & Social Media Influence**
     - Channel Mixed (combine online+offline) memiliki Average Order Value  tertinggi sebesar Rp4,5jt lebih tinggi dari In-Store sebesar Rp4,2jt dan Online murni sebesar Rp4,1jt. Customer yang berbelanja menggunkan lintas channel cenderung mengeluarkan nilai belanja yang lebih besar.
     - Menariknya level pengaruh media sosial (None/Low/Medium/High) tidak menunjukkan korelasi jelas dengan nilai belanja rata-rata purchase amount degan range Rp4,2 hingga 4,3 artinya paparan medsos saja belum tentu mendorong nilai transaksi lebih besar perlu digali lebih lanjut apakah dampaknya ke jumlah transaksi atau jenis kategori dibanding nilai per transaksi.
    
 5. **Purchase Intent**
    - Distribusi cukup merata  Purcahse Intent (niat motivasi di balik keputusan seseorang untuk membeli ) di 4 tipe yaitu Need-based  sebanyak 129, Wants-based sebanyak 126, Planned sebanyak  123 dan Impulsive sebanyak 121 tidak ada pola beli yang mendominasi.
    - Need-based dan Planned punya Average Order Value tertinggi sebesar Rp4,32 hingga 4,34jt sementara Impulsive justru AOV terendah yaitu sebesar  Rp4,14jt kontraintuitif biasanya impulsive buying dikaitkan dengan pengeluaran lebih besar tapi di data SuryaHub tidak demikian.
   
6. **High-Value Customer Profiling**
   - 100 customer top (20% dari populasi) menyumbang ~31% dari total revenue konsentrasi revenue tergolong sehat/tidak terlalu berisiko  bukan pola ekstrem (80/20) artinya SuryaHub tidak terlalu bergantung pada segelintir customer.  
