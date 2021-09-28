# IoT5-V3920046-TIE--Oktarinia-Rossa-A
Tugas IoT topic 5

PENJELASAN ALUR PROGRAM :

Pada gambar cisco diatas akan dibuat suatu simulasi untuk rumah pintar saat terjadi kebakaran. Nantinya saat sensor kebakaran mendeteksi adanya api maka 
jendela, pintu akan terbuka dan fire sprinkler akan menyala/memancarkan air. 
Untuk strukturnya digunakan alat window, door, fire sprinkler, fire monitor, server, pc, switch, dan digunakan heating element. 
Lalu ditambahkan suatu source code pada server : 
function setup(){ setDeviceProperty(getName(), 'IR', 900); } //script tersebut untuk heating element/api
Lalu, mensetting Ip, username, dan password pada setiap alat. Terakhir kita lakukan kondisi supaya window, door, dan fire sprinkler dapat ON saat ada api.
Setelah semua selesai, dekatkan heating element pada fire monitor supaya Window, door akan terbuka, dan fire sprinkle akan menyala 
