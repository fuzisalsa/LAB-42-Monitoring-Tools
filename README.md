# LAB-42-Monitoring-Tools
tanggal 24 agustus 2025

# monitoring tools

MikroTik RouterOS adalah sistem operasi berbasis Linux yang dikembangkan untuk perangkat jaringan. mikrotik routerOS juga  menyediakan berbagai alat monitoring untuk mengelola dan mengawasi performa jaringan secara real-time dan historis. Monitoring sangat penting untuk mendeteksi masalah, menganalisis trafik, dan menjaga stabilitas jaringan.

1. ping   
Fitur ping biasanya dipakai untuk monitoring secara langsung. misalkan ping ke internet, ke ip komputer lokal, ke server, dan lain sebagainya. Yang menjadi prioritas yang dimonitoring yaitu pada latency. fitur ping ini memanfaatkan protokol icmp untuk mengetahui latency dari tujuan atau destination tertentu.

2. traceroute  
Fitur Traceroute juga memanfaatkan ping juga tetapi lebih ditekankan pada jalur yang dilewati untuk menuju ke tujuan / destination tertentu. jadi dengan memakai traceroute, admin atau teman - teman dapat mengetahui jalur mana saja yang dilewati ketika menuju tujuan tertentu.

3. Graphing (RRD Tool) 
Fitur Graphing berupa grafik monitoring. Biasanya lebih ke penggunaan bandwidth. Fitur ini dapat dipakai untuk trafik pada ether sehingga dapat mengetahui penggunaan bandwidth dalam kurun waktu tertentu.

4. Queue  
Sebenarnya Queue lebih berfungsi untuk management bandwidth. Tetapi dengan memanfaatkan Queue tersebut, maka dapat mengetahui atau memonitoring penggunaan bandwidth pada komputer atau pelanggan.

5. Torch  
Monitoring Tool yang satu ini agak berbeda. Karena yang dimonitoring bukan latency atau bandwidth. Tetapi yang dimonitoring yaitu trafik. Makara dengan torch maka admin dapat mengetahui port dan ip yang dituju oleh sumbernya (yang dimonitoring). 

6. Netwatch  
Netwatch juga salah satu monitoring tools. Netwatch dapat berfungsi kalau dikombinasikan dengan fitur lain sehingga dapat dipakai untuk monitoring. Misalkan saja Netwatch dikombinasikan dengan email, messager telegram, dan lain sebagainya. Makara ketika kondisi tertentu dengan Netwatch tersebut dapat mengirimkan email terkait jaringan putus dan nyambung.

**SMS**   
Fitur SMS ini dapat dipakai untuk monitoring dengan memakai script tambahan. Dengan script pemanis tertentu maka dapat dipakai untuk monitoring. Mungkin ketika jaringan putus atau nyambung maka secara otomatis akan mengirimkan sms.

**SNMP (Simple Network Management Protocol)**  
Dengan memanfaatkan fitur SNMP ini, dapat dikombinasikan dengan MRTG Cacti untuk menciptakan monitoring. Ada banyak yang dapat dimonitoring misalkan bandwidth, lifetime, cpu, dan lain sebagainya.
unutk mengaktifkan nya di menu  **IP > SNMP > Enable**
Setelah aktif, server monitoring bisa mengambil data seperti: CPU usage, bandwidth per interface, uptime, dan lainnya.

**The Dude**   
Yang terakhir yaitu The Dude. Mungkin aplikasi ini bangkit sendiri. Tetapi dengan memanfaatkan SNMP yang ada di Mikrotik RouterOS maka dapat memonitoring banyak hal. menyerupai monitoring penggunaan bandwidth, latency, dan lain sebagainya. serta Bisa memantau banyak perangkat dan menggambarkan topologi jaringan secara grafis.

# kesimpulan 
MikroTik menyediakan berbagai tools bawaan yang sangat berguna untuk memantau dan menganalisis jaringan secara real-time maupun historis.
