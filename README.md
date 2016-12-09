# Guarding-My-Network

Project Webfig Untuk Http Proxy Menggunakan Squid yang bertitik Fokus kepada User
Dalam project ini setiap user memiliki hak akses,kecepatan bandwidth dan waktu aktif yang berbeda.


# Bagaimana Itu Bekerja

# UserManager
		1. Menggunakan Authentication Squid Mysql http://wiki.squid-cache.org/ConfigExamples/Authenticate/Mysql
		2. User dan Password digunakan dalam dua hal untuk memasuki web ( Admin Maupun Bukan ) dan Untuk Proxy Authentication
		3. User Memiliki Beberapa Atribut Yaitu 
										a. Profile Picture tersimpan di /usr/share/gmn
