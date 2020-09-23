# newspaper

#!/bin/bash

echo "Selamat Datang Di Newspaper"
sleep 1
echo "___________________________"
sleep 1
echo "(1). Perkenalan Diri"
echo "(2). Breaking News For U"
read -p "Pilih Salah Satu :" pilih;
if [ $pilih = "1" ]
then
    echo "Perkenalan Diri"
    read -p "Nama :" 
    read -p "Sekolah :"
    echo "Terima Kasih Kak Gita Sudah Diisi Semua..."
    read -p $back
elif [ $pilih = "2" ]
then 
    echo "Hai Git Mau Serius Dikit Nih..."
    sleep 1
    echo "Salah satu hal yang paling menyedihkan dalam hidup adalah ketika kita takut kehilangan seseorang yang bahkan bukan milikmu."
    sleep 2
    echo "Dan itu terbukti. Sekarang, Aku takut kehilangan dirimu. Aku begitu takut akan kehilangan kita yang selalu bersama:("
    sleep 3
    echo "Cinta kadang datang secara tiba-tiba. Kepada siapa, kapan, dan bagaimana cinta itu bisa datang. Kita tidak bisa menyalahkan cinta, karena semua telah direncanakan oleh Tuhan."
    sleep 4
    echo "Dan sekarang, aku hanya bisa mengagumimu tanpa bisa memilikimu:("
fi
