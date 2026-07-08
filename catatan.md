🔐 Untuk Authentication (langsung sekalian)
✅ Spring Security

Nanti JWT kita tambahkan lewat dependency di pom.xml karena biasanya tidak ada di Spring Initializr.

🚀 Redis

Belum dulu.

Kalau CRUD Hotel dan Login sudah selesai, baru tambahkan:

Spring Data Redis

📩 RabbitMQ

Belum dulu.

Tambahkan ketika mulai membuat Notification Service atau event-driven communication.

📁 Upload File

Belum perlu dependency tambahan. Spring Web sudah mendukung upload file menggunakan MultipartFile.

POST	/api/hotels	Tambah hotel
GET	/api/hotels	Semua hotel
GET	/api/hotels/{id}	Detail hotel
PUT	/api/hotels/{id}	Update hotel
DELETE	/api/hotels/{id}	Hapus hotel
