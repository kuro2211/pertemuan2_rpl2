**RPL Pertemuan 2 – Penerapan OOP (Inheritance, Overriding, Polymorphism)**

Repository ini berisi contoh penerapan konsep Object-Oriented Programming (OOP) dalam Java.
Pada pertemuan ini dipelajari cara membuat class, inheritance, method overriding, serta penggunaan objek dalam main program.

**Struktur Kelas**

Program terdiri dari beberapa kelas:

User (kelas induk / parent class)

Admin (turunan dari User)

Buyer (turunan dari User)

Seller (turunan dari User)

Setiap subclass mewarisi method login() dan logout() dari User, serta dapat menambahkan atau mengubah perilakunya.

**Konsep OOP yang Digunakan** 

🔹 1. Inheritance (Pewarisan)

Subclass seperti Admin, Buyer, dan Seller mewarisi atribut dan method dari kelas User.

🔹 2. Method Overriding

Buyer dan Admin melakukan override method login() dan logout() untuk memberikan perilaku yang berbeda dari User.

🔹 3. Polymorphism

Objek yang berbeda (Buyer, Admin, Seller) memiliki versi perilaku masing-masing walaupun memiliki method yang sama dari User.

<br>
